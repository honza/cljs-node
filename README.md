cljs-node
=========

cljs-node is a [Leiningen][1] template for projects that use [ClojureScript][2]
and target nodejs.

[1]: http://leiningen.org
[2]: https://github.com/clojure/clojurescript

It gives you a `project.clj` file with

* Clojure
* cljs-build
* piggieback nREPL
* Simple optimizations

Your sources will go into `src/` and compiled javascript will be placed in the
root directory as a simple file.

Usage
-----

```
$ lein new cljs-node monkey
$ cd monkey
$ lein cljsbuild once
$ node monkey.js
Hello world
```

License
-------

BSD, short and sweet
