# Isabelle/jEdit Macros

This repository contains a number of macros for Isabelle/jEdit.

To install them, you need to copy the `.bsh` files to
`$JEDIT_SETTINGS/macros/`.
They will then appear under `Macros` in jEdit.

To bind them to a shortcut, go to `Global Options > Shortcuts` and find them in that list.

The repository currently contains the following macros for toggling different types of "comments". If a text is selected, they
will surround it with the corresponding comment markers, else they will attempt to uncomment at the current cursor position.
- `cancel.bsh`: Add the cancel marker `⌦‹ ›`
- `comment.bsh`: Add the comment marker `― ‹ ›`
- `hide.bsh`: Add markers to hide enclosed Isabelle text from the PDF output `(*<*) (*>*)`
- `old_comment.bsh`: Add ML-style comment `(* *)`