# Warning

**************************************************************************

**NOTE:** these snippets are **no longer** actively maintained. For
the latest actively maintained snippets, organised into a package
see [https://github.com/mpenet/clojure-snippets](https://github.com/mpenet/clojure-snippets)

This repo is kept only for reference purposes

**************************************************************************

# Previously

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
