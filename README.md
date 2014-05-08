## libuv webserver

An hello-world webserver in C using [libuv](http://github.com/joyent/libuv) and
[http-parser](https://github.com/joyent/http-parser) taken from [philips](https://github.com/philips/libuv-webserver).

## Getting Started
Developing C across different environments can be particularily annoying. By using [Bowery](http://bowery.io) we can develop against our production enviornment.
```
$ ulimit -n 4096
$ git submodule update --init
$ bowery connect
$ bowery logs # in a new tab
```
