# GTT (Google Trends Tools)
The R package __GTT__ includes functions for additional Google Trends handling.

Currently the following functions are available:

1. kgraph is a function which obtains Google Knowledge Graph entities. These entities can be used for performing a topic search in Google Trends. The difference between topic and keyword based search is described [here](https://support.google.com/trends/answer/4359550). Note that you will need a Google Account and API key ([see here how](https://developers.google.com/knowledge-graph/how-tos/authorizing)).

Planned extensions include
1. Function which will combine Goolge Trends series to get long high frequency;
2. Scaling function to normalise Google Trends series


### Installation
For installation from github use the following R code by using devtools:

<pre><code> if (!require("devtools")){install.packages("devtools")}
devtools::install_github("mamut86/GTools") </code></pre>
