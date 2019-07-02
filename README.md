### DBDiagrams-mode

## What
[dbdiagrams.io](https://dbdiagrams.io) uses a dsl to describe entities which it then visualizes.
This is a major mode that runs off of `.dbd` files that tries to emulate the editing experience of the dsl.

## Why?
As much as I am enamored with the solution, I still find the editing experience from emacs(spacemacs) preferable
to the online editor, as I can't get my vim bindings in the text box. 

## Installation
This is a bit hacky as I am still rather unfamiliar with the right way to publish elisp code.
`cd ~/.emacs.d/private/local`
`git clone https://github.com/ccod/dbd-mode`
`edit ~/.spacemacs`

within `dotspacemacs/user-config`
add `(load-file "~/.emacs,d/private/local/dbd-mode/dbdiagram-mode.el")`

![demo of lang-mode](https://github.com/ccod/dbd-mode/blob/master/syntax-demonstration.png)

## TODO:
- hook into the autocomplete mode
- hook into flycheck to point out syntax errors
