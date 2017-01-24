Truth Table Generator
=====================

This is a JavaScript program which will generate a truth table given a well-formed formula of sentential logic. You can enter multiple formulas separated by commas to include more than one formula in a single table (e.g. to test for entailment). Tables can be displayed in html (either the full table or the column under the main connective only), plain text (for pasting into a text document), or LaTex. You can also select which pair of symbols to use for the two truth values.

The output characters used for the various connectives can be changed by modifying the `htmlchar()`, `txtchar()`, and `latexchar()` functions at the beginning of `truthtable.js`.

A live version of the program is [here](http://mrieppel.net/prog/truthtable.html).