---
layout: article
titles:
  # @start locale config
  en      : &EN       Home
  # @end locale config
key: page-about
---




```{js logo-js, echo=FALSE}
$(document).ready(function() {
  $('#header').parent().prepend('<div id=\"logo\"><img src=\"Images/Departmental_Logo.png\" style=\"position:absolute; top:0; right:0; padding:10px; height:120px\"></div>');
  $('#header').css('margin-right', '120px')
});
```

![](Images/Departmental_Logo.png)


```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

## R Markdown

This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:

```{r cars}
summary(cars)
```

## Including Plots

You can also embed plots, for example:

```{r pressure, echo=FALSE}
plot(pressure)
```

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.