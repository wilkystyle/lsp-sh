# lsp-sh

Bash support for lsp-mode using [Mads Hartmann's bash-language-server](https://github.com/mads-hartmann/bash-language-server)

## Configuration

You will need to call `lsp-sh-enable` when editing `.sh` files. You can use the following in your Emacs init file:

```lisp
(add-hook 'sh-mode-hook #'lsp-sh-enable)
```
