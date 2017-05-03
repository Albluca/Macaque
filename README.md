-   [Intalling rROMADash](#intalling-rromadash)
-   [Using rROMADash](#using-rromadash)

This package provides a shiny interface that can be used to complement
the [rRoma R package](https://github.com/Albluca/rRoma).

Intalling rROMADash
===================

The rROMADash package relies on the `rRoma` package, which is need to e
installed via `devtools`

    if(!requireNamespace("devtools")){
      install.packages("devtools")
    }
    devtools::install_github("Albluca/rROMA")

The other package needed to use the interface will be installed
automatically by R is not already available in the system.

Using rROMADash
===============

To launch the interface it is sufficient to type to following lines of
code:

    library(rRomaDash)
    rRomaDash()

It is also possible to enable interactivity (via the `plotly` package),
by typing

    library(rRomaDash)
    rRomaDash(Interactive = TRUE)

Note that the interactivity is still experimental and may not work
properly under certain system conditions.