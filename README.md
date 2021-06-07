# org-cite-csl-activate
An experimental CSL-based activation processor for Org citations, which
fontifies citations using rendered previews generated by `citeproc-el`. In
addition, tooltips over citations show a `mini bibliography' of the items
referred to.

## Requirements

+ Up-to-date `wip-cite-new' Org development branch.
+ The [citeproc-el](https://github.com/andras-simonyi/citeproc-el) library.

## Installation

Drop `oc-csl-activate.el` somewhere on your load path.

## Usage

The provided activation processor can be selected by executing

``` emacs-lisp
(require 'oc-csl-activate)
(setq org-cite-activate-processor 'csl-activate)
```

In addition, `cursor-sensor-mode` must be turned on in the Org buffer.

## Limitations
This is alpha quality code, you will certainly encounter all kinds of problems
and glitches!




