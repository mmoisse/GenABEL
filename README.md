# GenABEL

This is a fork of the CRAN R package repository, addapted to support datasets with more than 4M entries by loading a part of the variants.

## Install
```
if(!require(devtools)) { 
   install.packages("devtools"); 
   library(devtools)
}

install_github("mmoisse/GenABEL")
```
