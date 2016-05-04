  makeprogress
================

Makeprogress is a wrapper for `make` to show a progress bar instead of the
usual output. It simply replaces the `make` command and uses `pv` to render
the progress bar.

  Usage
---------

`makeprogress -j 2 SOME_OPTION=something some_target`
