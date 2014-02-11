# Fronteers in Right-to-Left

This is a demo created for a presentation for [Fronteers](http://fronteers.nl),
showing how easy it is to switch a site from left-to-right to right-to-left
using Sass.

The change is made by changing the `dir="ltr"` attribute on the `<html>` tag
to `dir="rtl"` and changing `$dir: ltr;` to `$dir: rtl;` in the Sass source.

## Compiling the CSS

Run the Sass watcher:

    sass --watch fronteers.scss:fronteers.css

Tested on Sass 3.3.0.rc.2.
