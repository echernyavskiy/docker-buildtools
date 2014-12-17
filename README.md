Docker Build Tools
==================

Simple yet useful Docker image based on `debian:jessie`, providing a set of
build tools:

* [Composer](https://getcomposer.org/) (using [HHVM](https://getcomposer.org/));
* [Bundler](http://bundler.io/);
* [NPM](https://www.npmjs.com/);
* [Bower](http://bower.io/).


Usage
-----

    $ docker run --rm buildtools composer --version
    Composer version 1.0-dev

    $ docker run --rm buildtools bundle --version
    Bundler version 1.7.4

    $ docker run --rm willdurand/buildtools npm --version
    1.4.28

    $ docker run --rm buildtools bower --version
    1.3.12
