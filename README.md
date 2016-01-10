This is a forked version of [h2o's](https://github.com/h2o) http server written in C of the same name - [h2o](https://github.com/h2o/h2o).

It was forked from commit [c6c7e5ba77b593825bdbe20d439695d26114042b](https://github.com/h2o/h2o/commit/c6c7e5ba77b593825bdbe20d439695d26114042b).

The goal of this fork is to turn h2o into a fast, minimalist, middleware, web app framework - much like [Express](http://expressjs.com/) is for node.js.

Below is the start of original README.



H2O - an optimized HTTP server with support for HTTP/1.x and HTTP/2
===

[![Build Status](https://travis-ci.org/h2o/h2o.svg?branch=master)](https://travis-ci.org/h2o/h2o)

Copyright (c) 2014-2016 [DeNA Co., Ltd.](http://dena.com/), [Kazuho Oku](https://github.com/kazuho/), [Tatsuhiko Kubo](https://github.com/cubicdaiya/), [Domingo Alvarez Duarte](https://github.com/mingodad/), [Nick Desaulniers](https://github.com/nickdesaulniers/), [Marc Hörsken](https://github.com/mback2k), [Masahiro Nagano](https://github.com/kazeburo/), Jeff Marrison, [Daisuke Maki](https://github.com/lestrrat/), [Laurentiu Nicola](https://github.com/GrayShade/), [Justin Zhu](https://github.com/zlm2012/), [Tatsuhiro Tsujikawa](https://github.com/tatsuhiro-t), [Ryosuke Matsumoto](https://github.com/matsumoto-r), [Masaki TAGAWA](https://github.com/mochipon), [Masayoshi Takahashi](https://github.com/takahashim), [Chul-Woong Yang](https://github.com/cwyang), [Shota Fukumori](https://github.com/sorah)

H2O is a new generation HTTP server.
Not only is it very fast, it also provides much quicker response to end-users when compared to older generations of HTTP servers.

Written in C and licensed under [the MIT License](http://opensource.org/licenses/MIT), it can also be used as a library.

For more information, please refer to the documentation at [h2o.examp1e.net](https://h2o.examp1e.net).
