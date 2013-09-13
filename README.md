simple-mf-grid
==============

It's a simple mobile-first grid, but who am I to judge if you misinterpret it.

[http://srosengren.github.io/simple-mf-grid/](http://srosengren.github.io/simple-mf-grid/)

## Usage

Simply include the smfgrid.css on your site or use the LESS in your project.

## Markup

A `.row` can be put anywhere on the page and will have a max size of 1170px. Adding the `.greedy` utility class to it will make the row fill any container, including the browser no matter the width.

You would most likely put `.col-X-N` elements in side of rows. The X is the size of the screen that the column targets (pt, t, d). The N is the number of columns your column should span on the specified screen size and it goes up to 12 (rows can be nested if you need a larger amount of columns). 

*  `.col-(1-12)` The default span width (unless overridden).
*  `.col-pt-(1-12)` Overrides any prior span width when the screen width is > 480px.
*  `.col-t-(1-12)` Overrides any prior span width when the screen width is > 768px.
*  `.col-d-(1-12)` Overrides any prior span width when the screen width is > 980px.
