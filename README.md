# cljs-test-example

Example project with `cljs.test`, enabling auto-test on cljsbuild.

This is a fork of [nvbn/cljs-test-example](https://github.com/nvbn/cljs-test-example), with one change made to <code>project.clj</code>: to enable cljs tests to be run everytime cljsbuild compiles changes.

This is done with <code>:notify-command</code> under the <code>:test</code> build.

More info:
 - https://nvbn.github.io/2015/06/08/cljs-test/
 - http://noprompt.github.io/clojurescript/testing/ruby/2014/01/25/autotesting-clojurescript.html
 - http://lab.brightnorth.co.uk/2015/01/27/unit-and-browser-testing-om-clojurescript-applications/

