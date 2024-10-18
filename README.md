# GeneScoreR Package
Gene Scoring from Genomic Count Tables

GeneScoreR is an R package that automatically calculates gene scores from gene count tables, providing two methods for scoring: the z-score method, which requires a table of samples being scored and a count table, and the geometric mean method, which does not rely on control samples.

## Installation:

Paste the following code into the R console

if (!requireNamespace("devtools", quietly = TRUE)) {
  install.packages("devtools")}
  
library(devtools)

devtools::install_github("ArisSyntakas/GeneScoreR")

library(GeneScoreR)
