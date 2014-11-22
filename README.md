
Here are two of the EGAP methods guides. The prettiest looking HTML comes from
using the ``render`` function from the
[rmarkdown](http://rmarkdown.rstudio.com/) package within R. Before trying to
compile these documents, you will need to have installed the R
packages in ``thepkgs``:

```
thepkgs<-c("AER","CausalGAM","ICC","RItools","lme4","lmtest","mediation","parallel","quantreg","sandwich","rmarkdown","knitr")
install.packages(thepkgs,dependencies=TRUE)

```

Alternatively, if you have [pandoc](http://johnmacfarlane.net/pandoc/) and a Unix environment (like Mac OS X), you can use the scripts that we include.

```

./knit2html.sh ClusterRandomEGAP

./knit2html.sh EgapOutline

```



