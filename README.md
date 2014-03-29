Truth Table Generator
=====================

This program generates a truth table given a well formed formula of sentential logic.  Enter multiple formulas separated by commas to include more than one formula in a single table.  Select "Full Table" to show all columns, and "Main Connective Only" to show only the column under the main connective.  Select "Text Table" to produce a plain text table, and "LaTex Table" to produce a  table formatted for Latex.

See the index.html for a description of the expected input syntax.  The output characters used for the various connectives can be easily changed by modifying the `htmlchar()`, `txtchar()`, and `latexchar()` functions at the beginning of `truthtable.js`.