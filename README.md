Install yasnippet via the Emacs package manager.

Then:

```
git clone http://github.com/swannodette/clojure-snippets ~/.emacs.d/snippets/clojure-mode
```

Or whatever location you prefer. Then In your `.emacs` you should have
something like the following

```elisp
(when (require 'yasnippet nil 'noerror)
  (progn
    (yas/load-directory "~/.emacs.d/snippets")))
```
