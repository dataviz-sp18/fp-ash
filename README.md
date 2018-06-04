### visualizing scientific results from a study of relational cognition and gesture

Visualizing experimental data is highly conventionalized across many scientific disciplines. For example, mean differences are typically presented as bar plots with error bars and brackets that show significant differences between mean pairs. This project explores some possible alternatives to this and other standards of visualization (or lack thereof) in reporting data and results with an eye toward leveraging the possibilities of visualization to make the quantitative aspects of empirical results tell a story that is more functional and insightful. 

The results of this exploratory effort can be viewed on **[this GitHub Page](https://uc-dataviz.github.io/fp-ash/)**.

### setup

The seed was set to 1618, and the following packages were used to generate this output (see 

knitr::opts_chunk$set(echo = TRUE, fig.width = 6, fig.asp = 0.618, echo = FALSE)

library(rmarkdown)
library(ggplot2)
library(ggsignif)
library(plotly)
library(ggraph)
library(igraph)
library(waffle)
library(ggpubr)
library(cowplot)
library(wesanderson)
library(data.table)
library(tidyverse)

set.seed(1618)



#### acknowledgements

I would like to thank *Kensy Cooperrider* for his mentorship and supportive collaboration throughout all phases of the study from which this data is drawn, *Susan Goldin-Meadow* and everyone at the *Goldin-Meadow Lab* for valuable feedback. I also thank Professor *Benjamin Soltoff* for informative lectures, helpful resources and challenging assignments that encouraged using a variety of tools to learn by doing, all of which fostered my understanding of the value of considering the subtleties of data visualization.


