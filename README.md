Hy
==

[![Build Status](https://travis-ci.org/hylang/hy.png?branch=master)](https://travis-ci.org/hylang/hy)
[![Downloads](https://pypip.in/d/hy/badge.png)](https://crate.io/packages/hy)
[![version](https://pypip.in/v/hy/badge.png)](https://crate.io/packages/hy)
[![Coverage Status](https://coveralls.io/repos/hylang/hy/badge.png)](https://coveralls.io/r/hylang/hy)

![](https://raw.github.com/hylang/shyte/18f6925e08684b0e1f52b2cc2c803989cd62cd91/imgs/xkcd.png)

Lisp and Python should love each other. Let's make it happen. [Try it](http://try-hy.appspot.com/).


Hylarious Hacks
---------------

[Django + Lisp](https://github.com/paultag/djlisp/tree/master/djlisp)

[Python sh fun](https://twitter.com/paultag/status/314925996442796032)

[Hy IRC bot](https://github.com/hylang/hygdrop)

[miniKanren in Hy](https://github.com/algernon/adderall)


What is Hy?
-----------
Hy is a LISP-1 living off the restricitons imposed by the Python runtime, while delivering all the goods from Lisp. Python versions 2.6 all the way up to, and including, 3.4 and PyPy is supported. Bidirectional interop gives you the possibilities of using Hy and Python together as one, and not two separate languages. We got
![Macros](http://docs.hylang.org/en/latest/language/api.html#defmacro),
![CLOS Syntax](http://docs.hylang.org/en/latest/language/api.html#defclass) for objects, 
![Reader Macros](http://docs.hylang.org/en/latest/language/readermacros.html), and even
![loop/recur](http://docs.hylang.org/en/latest/contrib/loop.html) for those cases where you need recursion!


OK, so, why do this sorcery?
----------------------------
Hy proves that the Python runtime is not completely different from the LLVM or JVM. You can remove the syntax provided by Python, and replace it with anything. There is not really any big limits when working with the AST provided. Haskell, PHP or Befunge, you could do all of it! Go do it!

```
I wrote Hy to help people realize one thing about Python:
It's really awesome.
Oh, and lisps are neat.
```
~ Paul Tagliamonte, Hy creator & BDFL



![](http://i.imgur.com/QbPMXTN.png)

(fan art from the one and only [doctormo](http://doctormo.deviantart.com/art/Cuddles-the-Hacker-372184766))


Project
-------

* Code: https://github.com/hylang/hy
* Docs: http://hylang.org/
* Quickstart: http://hylang.org/en/latest/quickstart.html
* Bug reports: We have no bugs! Your bugs are your own! (https://github.com/hylang/hy/issues)
* License: MIT (Expat)
