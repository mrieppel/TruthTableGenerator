Truth Table Generator
=====================

This program generates a truth table given well formed formulas of sentential logic.  It can produce a joint truth table for multiple formulas (separated by commas), and show either the full table or only the column under the main connective.  Output tables can be in HTML, plain text, or LaTeX. 

The output characters used for the various connectives can be easily changed by modifying the `htmlchar()`, `txtchar()`, and `latexchar()` functions at the beginning of `truthtable.js`.

A live version of the program is [here](http://mrieppel.net/prog/truthtable.html).