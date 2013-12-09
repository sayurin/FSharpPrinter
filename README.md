FSharpPrinter
=============

 * Camlp4Printers/Camlp4FSharpPrinter.patch
   diff from https://github.com/ocaml/ocaml/blob/4.01/camlp4/Camlp4/Printers/OCaml.ml
 * Camlp4Printers/Camlp4FSharpPrinter.ml
   the patched file (version 4.01.0).

To compile this,
```
$ ocamlc -I +camlp4 -pp camlp4rf -c Camlp4FSharpPrinter.ml
```
To use this,
```
$ camlp4of -printer Camlp4FSharpPrinter -o fsharp-source.ml ocaml-source.ml
```
