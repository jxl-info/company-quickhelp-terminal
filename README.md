[![Build Status](https://travis-ci.com/jcs090218/company-quickhelp-terminal.svg?branch=master)](https://travis-ci.com/jcs090218/company-quickhelp-terminal)
[![MELPA](https://melpa.org/packages/company-quickhelp-terminal-badge.svg)](https://melpa.org/#/company-quickhelp-terminal)
[![MELPA Stable](https://stable.melpa.org/packages/company-quickhelp-terminal-badge.svg)](https://stable.melpa.org/#/company-quickhelp-terminal)
[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)


# company-quickhelp-terminal
> Terminal support for `company-quickhelp'.

This package extends [company-quickhelp'](https://github.com/expez/company-quickhelp)
for terminal support using [popup](https://github.com/auto-complete/popup-el).


## Usage

Just add these lines of code to your configuration, then it should be good to go.

```el
(with-eval-after-load 'company-quickhelp
  (company-quickhelp-terminal-mode 1))
```


## Contribution

If you would like to contribute to this project, you may either
clone and make pull requests to this repository. Or you can
clone the project and establish your own branch of this tool.
Any methods are welcome!
