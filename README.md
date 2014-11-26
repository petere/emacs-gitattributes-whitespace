This Emacs module sets `indent-tabs-mode`, `tab-width`, as well as
`whitespace-style` (from `whitespace-mode`) according to the settings
of the
[gitattributes(5)](https://www.kernel.org/pub/software/scm/git/docs/gitattributes.html)
whitespace setting for the file (as best as they can be matched).  If
the file is not in a Git repository, or there are no gitattributes
set, then nothing happens.
