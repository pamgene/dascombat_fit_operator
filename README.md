# DasCombat fit operator

##### Description

The `dascombat_fit_operator` is a operator to obtain a fitted model based on the
DasCOMBAT software developed at PamGene. This fitted model can then be used to 
make predictions in the `dascombat_prediction_operator`.

##### Usage

Input projection|.
---|---
`y-axis`        | the y values
`row`           | the peptide IDs
`column`        | the barcodes
`colors`        | the reference batches

Output relations|.
---|---
`model`        | character, name of the DASCOMBAT model (to be used with other dascombat_prediction_operator)

##### Details

Details on the computation can be found in the `pamgene::pgbatch` and 
`SVA::combat` applications.

##### See Also

[dascombat_shiny_fit_operator](https://github.com/tercen/dascombat_shiny_fit_operator)
, [dascombat_prediction_operator](https://github.com/tercen/dascombat_prediction_operator)
