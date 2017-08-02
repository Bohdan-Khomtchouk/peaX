[![Travis-CI Build Status](https://travis-ci.org/Bohdan-Khomtchouk/peaX.svg?branch=master)](https://travis-ci.org/Bohdan-Khomtchouk/peaX)
[![MIT license](http://img.shields.io/badge/license-MIT-blue.svg)](http://opensource.org/licenses/MIT)
[![GitHub version](https://badge.fury.io/gh/Bohdan-Khomtchouk%2FpeaX.svg)](https://badge.fury.io/gh/Bohdan-Khomtchouk%2FpeaX)
# peaX

`peaX` is an R data package that provides human transcription factor and histone modification ChIP-seq peaks data from ENCODE and ROADMAP Epigenomics.  Files originally downloaded in bigBed format, converted to BED, and then tidied up to include only peak coordinates (chromosome number, peak start position, peak end position) in preparation for large-scale functional annotation.

### Installation instructions

You can install the current GitHub version using the [devtools](https://github.com/hadley/devtools) package and the following command in R:
```R
if (!require("devtools")) install.packages("devtools")
devtools::install_github("Bohdan-Khomtchouk/peaX")
```
And then:
```R
library(peaX)
```
