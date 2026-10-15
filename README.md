# The SysL Programming Language

The book on [sysl](https://github.com/sysl-lang/sysl), typeset with
[texish](https://github.com/edadma/texish).

```
texish main.texish
```

renders `main.pdf`. `main.texish` is the spine; each chapter is a file in `chapters/`. (The spine
cannot be called `book.texish`: a file beside the document named after a package replaces that
package, and the book is set with texish's `book` package.)
