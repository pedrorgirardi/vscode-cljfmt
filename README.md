# cljfmt

![cljfmt](images/web.png)

This extension is a [**cljfmt**](https://github.com/weavejester/cljfmt) wrapper to provide document and range formatting.

## Configuration

`cljfmt.indentation` - true if cljfmt should correct the indentation of your code. Defaults to true.

`cljfmt.insertMissingWhitespace` - true if cljfmt should insert whitespace missing from between elements. This will convert (foo(bar)) to (foo (bar)). Defaults to true.

`cljfmt.removeSurroundingWhitespace` -  true if cljfmt should remove whitespace surrounding inner forms. This will convert ( foo ) to (foo). Defaults to true.

`cljfmt.removeTrailingWhitespace` - true if cljfmt should remove trailing whitespace in lines. This will convert (foo) \n to (foo)\n. Defaults to true.


## Note

If you are looking for a Clojure & ClojureScript programming environment for **Visual Studio Code**, it's a good idea to check **Calva** and the other extensions.

If you already have **Calva** installed, please be aware that formatting may not work properly since both extensions will try to format your code.


## Acknowledgement

Thank you, James Reeves!


## Written in ClojureScript

Built with [Shadow CLJS](http://shadow-cljs.org/).