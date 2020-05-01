[![lifecycle](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)

# GTT (Google Trends Tools)
The R package __GTT__ includes functions for additional Google Trends handling.

Currently the following functions are available:

1. kgraph is a function which obtains Google Knowledge Graph entities. These entities can be used for performing a topic search in Google Trends. The difference between topic and keyword based search is described [here](https://support.google.com/trends/answer/4359550). Note that it is advised to use your Google API key for large queries ([see here how-to](https://developers.google.com/knowledge-graph/how-tos/authorizing)).

Planned extensions include
1. Function which will combine Goolge Trends time series for covering long time periods at high frequency;
2. Scaling function to normalise Google Trends series.


### Installation
For installation from github use the following R code by using devtools:
```r
if (!require("devtools")){install.packages("devtools")}
devtools::install_github("mamut86/GTT")
```
