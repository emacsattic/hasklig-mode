# hasklig-mode.el - Hasklig ligatures for emacs

[![](https://melpa.org/packages/hasklig-mode-badge.svg)](https://melpa.org/#/hasklig-mode)

1. Install the Hasklig font to `~/.fonts`.
2. Modify your emacs configuration `.emacs.d/init.el`.

Example configuration:

~~~ elisp
(set-face-attribute 'default nil
                    :family "Hasklig"
                    :height 200
                    :weight 'normal
                    :width 'normal)

(use-package hasklig-mode
  :hook (haskell-mode))
~~~
