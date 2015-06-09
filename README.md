# dotemacs_cask


## .emacs

```
(load (expand-file-name (concat (getenv "HOME") "/.emacs.d/init")))
```

## install

```
# install cask
$ curl -fsSL https://raw.githubusercontent.com/cask/cask/master/go | python

$ cd
$ git clone git@github.com:guan/dotemacs_cask.git .emacs.d
$ cd .emacs.d
$ cask install
```
