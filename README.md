# cljfmt

![cljfmt](images/web.png)

This extension is a wrapper for the [**cljfmt**](https://github.com/weavejester/cljfmt)  formatting tool. It provides a formatter for Clojure, ClojureScript and EDN code, so `Format Document` and `Format Selection` work as expected.


## Format on save

Change your settings to enable `cljfmt` to format your code on save:

`"editor.formatOnSave": true`


## Configuration

`cljfmt.indentation` - true if cljfmt should correct the indentation of your code. Defaults to true.

`cljfmt.insertMissingWhitespace` - true if cljfmt should insert whitespace missing from between elements. This will convert (foo(bar)) to (foo (bar)). Defaults to true.

`cljfmt.removeConsecutiveBlankLines` - true if cljfmt should collapse consecutive blank lines. This will convert (foo)\n\n\n(bar) to (foo)\n\n(bar). Defaults to true.

`cljfmt.removeSurroundingWhitespace` -  true if cljfmt should remove whitespace surrounding inner forms. This will convert ( foo ) to (foo). Defaults to true.

`cljfmt.removeTrailingWhitespace` - true if cljfmt should remove trailing whitespace in lines. This will convert (foo) \n to (foo)\n. Defaults to true.


## Note

If you are looking for a Clojure & ClojureScript programming environment for **Visual Studio Code**, it's a good idea to check **Calva** and the other extensions.

If you already have **Calva** installed, please be aware that formatting may not work properly since both extensions will try to format your code.


## Acknowledgement

Thank you, James Reeves!


## Written in ClojureScript

Built with [Shadow CLJS](http://shadow-cljs.org/).