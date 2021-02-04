# Overview

- Stand-alone portable C libraries. 
- Each folder includes a single .h .c pair which is independent of other files.
- There is no build, just copy paste *.h *.c file into your project. 
- CI runs on Linux, MacOS, FreeBSD and Windows with GCC, Clang and MSVC.

# Details
- 

### List

| Library                                                                 | Description                                                    |
|-------------------------------------------------------------------------|----------------------------------------------------------------|
| [array](array)                                                          | Generic array/vector                                           |
| [buffer](https://github.com/tezc/simple-c/tree/master/buffer)           | Buffer for encoding/decoding variables                         |
| [condition](https://github.com/tezc/simple-c/tree/master/condition)     | Condition wrapper with extra functionality                     |
| [crc32](https://github.com/tezc/simple-c/tree/master/crc32)             | Crc32c implementation                                          |
| [heap](https://github.com/tezc/simple-c/tree/master/heap)               | Min heap which can be used as max heap/priority queue as well  | 
| [ini](https://github.com/tezc/simple-c/tree/master/ini)                 | Ini parser                                                     |
| [linked list](https://github.com/tezc/simple-c/tree/master/linked-list) | Intrusive linked list                                          |
| [logger](https://github.com/tezc/simple-c/tree/master/logger)           | Logger                                                         |
| [map](https://github.com/tezc/simple-c/tree/master/map)                 | A high performance hashmap                                     |
| [math](https://github.com/tezc/simple-c/tree/master/math)               | Utility functions                                              |
| [memory map](https://github.com/tezc/simple-c/tree/master/memory-map)   | Mmap wrapper for Posix and Windows                             |
| [mutex](https://github.com/tezc/simple-c/tree/master/mutex)             | Mutex wrapper for Posix and Windows                            |
| [option](https://github.com/tezc/simple-c/tree/master/option)           | Cmdline argument parser. Very basic one                        |
| [perf](https://github.com/tezc/simple-c/tree/master/perf)               | Benchmark utility to get performance counters info             | 
| [queue](https://github.com/tezc/simple-c/tree/master/queue)             | Generic queue which can be used as dequeue/stack/list as well  |
| [rc4](https://github.com/tezc/simple-c/tree/master/rc4)                 | Random number generator                                        |
| [signal](https://github.com/tezc/simple-c/tree/master/signal)           | Signal handler (handling CTRL+C, print backtrace on crash etc) |
| [socket](https://github.com/tezc/simple-c/tree/master/socket)           | Pipe, TCP sockets, Epoll/Kqueue/WSAPoll for Posix and Windows  |
| [string](https://github.com/tezc/simple-c/tree/master/string)           | Length prefixed, null terminated C strings.                    |
| [thread](https://github.com/tezc/simple-c/tree/master/thread)           | Thread wrapper for Posix and Windows.                          |
| [time](https://github.com/tezc/simple-c/tree/master/time)               | Time and sleep functions for Posix and Windows                 |
| [timer](https://github.com/tezc/simple-c/tree/master/timer)             | Hashed timer wheel implementation for fast poll / cancel ops   |
| [uri](https://github.com/tezc/simple-c/tree/master/uri)                 | A basic uri parser                                             |

