# flycheck-swift3

A Swift syntax checker using Swift compiler frontend.

## Requirements

* Apple Emacs Lisp files for Swift
  * [swift-mode.el](https://raw.githubusercontent.com/apple/swift/master/utils/swift-mode.el)
  * [swift-project-settings.el](https://raw.githubusercontent.com/apple/swift/master/utils/swift-project-settings.el) (optional)
  * [inferior-swift-mode.el](https://raw.githubusercontent.com/apple/swift/master/utils/inferior-swift-mode.el) (optional)
  * [sil-mode.el](https://raw.githubusercontent.com/apple/swift/master/utils/sil-mode.el) (optional)
* [Flycheck](http://www.flycheck.org/)

## Installation

If you're an Emacs 24 user or you have a recent version of `package.el`, you can install `flycheck-swift3.el` from the [MELPA](https://melpa.org/) or the [MELPA Stable](https://stable.melpa.org/) repository.

In your `init.el`:

```elisp
(require 'flycheck-swift3) ; Not necessary if using ELPA package
(eval-after-load 'flycheck
  '(add-hook 'flycheck-mode-hook #'flycheck-swift3-setup))
```

## License

This software is licensed under the MIT License.

See the LICENSE file for details.
