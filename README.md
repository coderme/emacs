##  emacs configuration. 

## Features Summary
* Natural Keyboard shortcuts no F1..F13 keys needed )
* Support GO developement. 
* Support DART developement including Flutter. 
* Support beautifying CSS, HTML and JAVASCRIPT source codes.

## Setup
* Clone this repo into your local storage. ```git clone https://github.com/coderme/emacs.git```
* Rename emcas/emacs.cfg to $HOME/.emacs ```cp --backup=t emacs/emacs.cfg $HOME/.emacs```
* Create $HOME/.cache/.emacs directory ```mkdir -p $HOME/.cache/.emacs```
* Initialize packages from within emacs ```package-initialize```

## Go Setup
* Install Go into your bin [https://go.dev/dl/]
* Install gopls using the following command ```go install golang.org/x/tools/gopls@latest```

## Dart Setup
* Install dart in your path or use dart from flutter installation

## web-beautifier Setup
* install js-beautifier ```npm -g install js-beautify```

## Shortcuts
# ```C-o``` for ```goto-line```
# ```C-r``` for ```replace-string```
# ```C-h``` for ```replace-regexp```
# ```C-d``` for ```duplicate-line-or-region```
# ```C-z``` for ```neotree-toggle```
# ```C-a``` for ```treemacs```
# ```C-c C-n``` for ```treemacs-create-file```
# ```C-c C-d``` for ```treemacs-create-dir```
# ```C-1``` for ```flycheck-next-error```
# ```C-2``` for ```flycheck-previous-error```
# ```<M-right>``` for ```windmove-right```
# ```<M-left>``` for ```windmove-left```
# ```<M-up>``` for ```windmove-up```
# ```<M-down>``` for ```windmove-down```


## REFERENCES
* [https://emacs-lsp.github.io/lsp-mode/]
* [https://go.dev/]
* [https://pkg.go.dev/golang.org/x/tools/gopls]
* [https://emacs-lsp.github.io/lsp-mode/page/lsp-gopls/]
* [https://dart.dev/]
* [https://emacs-lsp.github.io/lsp-dart/]
* [https://github.com/bitwiseman/js-beautify]


