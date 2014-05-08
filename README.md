## libuv webserver

An hello-world webserver in C using [libuv][libuv] and
[http-parser][http-parser] taken from [philips](https://github.com/philips/libuv-webserver).

## Getting Started
Developing C across different environments can be particularily annoying. By using [Bowery](http://bowery.io) we can develop against our production enviornment.
```
$ ulimit -n 4096
$ bowery connect
$ bowery logs # in a new tab
```
