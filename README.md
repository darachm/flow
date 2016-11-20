# flow

Workflow and associated scripts for processing flow cytometry data.
To use, you should make and rename a copy of the 
`GreshamLabFlowWorkflow.Rmd` file. This is not a plug-and-play
script, this is a workflow guide on how to go about using these
scripts.

<!--
The overall strategy for using flow cytometry analysis is:
1. Perform gating for i) doublets, ii) debris and iii) fluorescence using an R script and save as .Rdata
2. Import gates and render Rmarkdown file in order to save report of work
-->

# organization

- `./src/` contains snippets of R code for functions and things.
- `./testData/` contains data and samplesheets for testing
- we oughta put those fcs files as example datasets on a public OSF
  account. So this example would download those as URL's for the 
  example, so it's reproducible. But then you just change the string 
  to do your local.
