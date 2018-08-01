Cloud Foundry Common Lisp Buildpack
===================================

This is a buildpack for running Common Lisp application
(optionally augmented with the power of [Quicklisp!][ql]) on
[everyone's favorite PaaS][cf].

**BIG OBNOXIOUS WARNING**

This is alpha.  You probably don't want to write in Common Lisp.
It's 2018 after all, and we ought not use languages from a
previous century.  Ageism ageism ageism!

Seriously, I'm just tinkering with this because I (a) like Cloud
Foundry and (b) am way more productive in Lisp.

Consider yourself warned.

Usage
-----

Near as I can tell, this is what you have to do to use this
buildpack:

```sh
cf push -b https://github.com/jhunt/cl-buildpack ...
```

But I guess we'll find out, now won't we?


[ql]: https://quicklisp.org
[cf]: https://cloudfoundry.org
