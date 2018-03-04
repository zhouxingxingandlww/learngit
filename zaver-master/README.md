Zaver
=====

Yet another fast and efficient HTTP server.


## programming model

* epoll
* non-blocking I/O
* thread-pool

## compile and run (for now only support Linux2.6+)

please make sure you have [cmake](https://cmake.org/) installed.
```
mkdir build && cd build
cmake .. && make
cd .. && ./build/zaver -c zaver.conf
```

## support

* HTTP persistent connection
* browser cache
* timer(use binary heap instead of rbtree used in Nginx)


