# event_loop.h
This is a [stb]-style single-header library providing event loop abstraction on top of [epoll].

## Usage:
To use this library, simply copy it into your project. Then, in one (only one!) C file:
```C
#define EVENT_LOOP_IMPLEMENTATION
#include "event_loop.h"
```
For practical usage example, see [example.c](example.c). Compile it with `gcc example.c`.
For documentation on each function, see the source code.

[stb]: https://github.com/nothings/stb
[epoll]: https://www.man7.org/linux/man-pages/man7/epoll.7.html
