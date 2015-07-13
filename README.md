# cbm - cycle by major-mode

## Installation:

Just put cbm.el in your load-path and require it:

```lisp
(require 'cbm)
```

It is recommended to bind `cmb-cycle` to a key:
```
(global-set-key (kbd "C-'") #'cbm-cycle)
```

## Usage:

This package provides one usefull command `cbm-cycle`, which cycles
through all buffers with the same major-mode as the current-buffer.
