# USF NLP Final Project - Structural Topic Modelling

For this project, I explored Structural Topic Modelling (STM) on Amazon reviews using R's `stm` package. 
The point of STM is to incorporate covariate information (i.e. document-level metadata) into a standard topic model. 
Some hypothesize that doing so helps latent topics better emerge. 

Here are some links about STM:  

* [Paper on STM](https://scholar.princeton.edu/files/bstewart/files/stmnips2013.pdf)
* [`stm`'s documentation](https://cran.r-project.org/web/packages/stm/vignettes/stmVignette.pdf)  
* [A helpful tutorial](https://github.com/dondealban/learning-stm)  

Data (Amazon's Health & Personal Care Category)

* [Product Reviews](http://snap.stanford.edu/data/amazon/productGraph/categoryFiles/reviews_Health_and_Personal_Care.json.gz)
* [Product Metadata](http://snap.stanford.edu/data/amazon/productGraph/categoryFiles/meta_Health_and_Personal_Care.json.gz)

Notebooks 

* [Preprocessing in Python](https://github.com/keryums/nlp/blob/master/nlp_stm_preprocessing.ipynb)
* [`stm`in R](https://github.com/keryums/nlp/blob/master/nlp_stm_final.Rmd) (This file is big so please download it.)
