# Simple Markdown Parser

You might ask why build yet another? The answer is I wanted a simple small and
fast markdown parser to build tools on top of. There are lots of tools that will
make html but I wanted just a simple AST (Abstract syntax tree) that any tool
can use to build what ever output format they wanted.

Since markdown can also have html this can also parse any html but it follows they
rules of markdown in that you can't mix them and it needs to be separated from
surrounding content by blank lines.

**This is still under development. I will make it version 1.0 once it is ready.**
