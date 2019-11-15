# GESIS workshop on Topic Modeling

Welcome to the 2019 GESIS workshop on Topic Modeling.

This page will be used to distribute the slides, handouts, and other materials for this course.

All material is free to re-use under the [CC-BY](LICENSE.md) license. 

## Useful links

+ [R for Data Science](https://r4ds.had.co.nz) - A free online book on data analysis in R
+ [Text Analysis in R](http://vanatteveldt.com/p/welbers-text-r.pdf) - Our tutorial on quantitative text anlaysis
+ [RStudio Cheat Sheets](https://rstudio.com/resources/cheatsheets/) - Summaries of useful R commands
+ [ggplot Gallery](https://www.r-graph-gallery.com/ggplot2-package.html) and [data-to-viz](https://www.data-to-viz.com/) for inspiration on visualization
+ [r-course-material](https://github.com/ccs-amsterdam/r-course-material) - Our handouts on tidyverse, statistics, and text analysis in R
+ [rvest blog post from the author](https://blog.rstudio.com/2014/11/24/rvest-easy-web-scraping-with-r/) [rvest mini demo](https://gist.github.com/vanatteveldt/ad6e6960eeac9ebd03b7ab1ce983008f)

## Preparation

+ Download & install R from: https://cran.r-project.org/
+ Download & install RStudio from: https://www.rstudio.com/
+ Install packages with the following R commands:

```{r}
install.packages(‘tidyverse’)
install.packages(‘quanteda’)
```

## Day 1: Introduction to R (optional)

+ Morning Session: Introduction to R
  + Slides: [[Introduction to R](https://docs.google.com/presentation/d/1Dp6SN93-HqXOurZYkWRjM8TST1-OQGm6TpEnz1x-lHU/edit?usp=sharing)]
  + Handouts: 
    [[Getting Started](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/R_basics_1_getting_started_short.md)], 
    [[R Basics](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/R-tidy-4-basics.md)]
 + Afternoon Session: Data analysis and Visualization
   + Slides: [[Tidyverse and ggplot](https://docs.google.com/presentation/d/1-KExaoUYrWgaM__raFSaUnu0UKwIQ5icn8iVZgKHLU4/edit?usp=sharing)]
   + Handouts: 
     [[Tidyverse basics](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/R-tidy-5-transformation.md)]
     [[Summarizing data](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/R-tidy-5b-groupby.md)]
     [[Visualizing data](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/r-tidy-3_7-visualization.md)]
   + Bonus handouts: 
     [[Reshaping data](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/r-tidy-12-reshaping.md)]
     [[Combining data](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/R-tidy-13a-joining.md)]

## Day 2: Quantitative Text Analysis and Topic Modeling

+ Morning Session: Introduction to Automatic Text Analysis
  + Slides: 
	[[Preprocessing](https://docs.google.com/presentation/d/11MuZe1qVrOPNRnvFTP7ffT5E_AJM0Cly6r6nAxSC4bM/edit?usp=sharing)]
  + Handouts: 
	[[Text analysis with Quanteda](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/R_text_3_quanteda.md#step-1-importing-text-and-creating-a-quanteda-corpus)]
+ Afternoon Session: Running and Validating Topic Models
  + Slides: 
	[[Topic modeling](https://docs.google.com/presentation/d/1nRT5bmtkNDhcUATU61pW4TIuKQC59QMbjY8dpPEeMrQ/edit?usp=sharing)]
        [[Validation](https://docs.google.com/presentation/d/1VvckL6NGsh1Q_ekEAGqYoNCwLD1g1BmbSSsCKxnUqB8/edit?usp=sharing)]
  + Handouts: 
	[[LDA topic modeling](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/r_text_lda.md)]
	[[Topic browsers](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/R_text_topicbrowser.md)]

## Day 3: Advanced issues in Topic Modeling

+ Morning Session 1: Technical Details of Topic Modeling
  + Slides:
    [[Technical Details of LDA](https://docs.google.com/presentation/d/171QIqkYDo2fR48mkGmPeoeHkp58xhRDXXtcrOTh3l-o/edit?usp=sharing)]
    [[Validation and Perplexity](https://docs.google.com/presentation/d/1v46wjjlQifmHxlRerVUVAuZqosz-cjxFUtbqb3klRAs/edit?usp=sharing)]
  + Handouts: 
  [[SVD](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/SVD.md)] 
  [[Iterations Animated](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/gibbs_animate.R)]
  [[Understanding alpha](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/understanding_alpha.md)]
  [[Gibbs Sampling](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/gibbs.R)]
  [[Determining the number of topics](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/R_text_LDA_perplexity.md)]
+ Afternoon Session: Structural Topic Models
  + Slides: [[LDA Variants & Structural Topic Models](https://docs.google.com/presentation/d/1rp9BwFGJV0E56xCdQoQWfju46Yk4ix5uLYP-4MHfJ-Y/edit?usp=sharing)]
  + Handouts: [[Structural Topic Models](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/r_text_stm.md)]
    [[STM Vignette](https://github.com/bstewart/stm/blob/master/inst/doc/stmVignette.pdf?raw=true)]
