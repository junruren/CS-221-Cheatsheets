# LaTeX Cheatsheets for CS 221

## Credits:

* LaTeX template inspired by https://tex.stackexchange.com/questions/8827/preparing-cheat-sheets
* Cheatsheet contents inspired by https://stanford.edu/~shervine/teaching/cs-221/

## How to edit

The gist is to organize different modules into their own `.tex` files under the
`topics/` directory, and then reference each module's `.tex` file from within
the main cheatsheet file through

```tex
\input{topics/MODULE_NAME.tex}
```