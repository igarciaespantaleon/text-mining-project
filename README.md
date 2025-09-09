# From *College Dropout* to *Ye*: Kanye West’s Lyrical Evolution

This repository contains the group project for our **Text Mining** course.  
We analyze Kanye West’s lyrics across nine studio albums (2004–2018) using text-mining techniques to explore how language, themes, and sentiment shift over time.

## Contents
- **Garcia-Espantaleon_Ramos_Romero_TMFinalAssignment.Rmd** — the full R Markdown source code of the analysis.  
- **Garcia-Espantaleon_Ramos_Romero_TMFinalAssignment.html** — the rendered HTML version.  

The data are imported directly from a public GitHub repository and are not stored here.

## How to reproduce
Open the `.Rmd` report in RStudio and knit to HTML.  
Requires common R text-mining packages: tidyverse, tidytext, quanteda, widyr, ggraph, igraph, wordcloud, RColorBrewer, textstem.

## Methods
- **Text preprocessing**: data cleaning, tokenization, stopword removal, lemmatization.  
- **Exploratory features**: word frequency, TF, and TF–IDF across albums.  
- **Sentiment analysis**: NRC, Bing, and AFINN lexicons to track emotional variation.  
- **Insult analysis**: frequency and distribution of slang/offensive language.  
- **Word co-occurrence networks**: to visualize recurring themes.

## Authors
Irene García-Espantaleón Artal, Jorge Ramos Val and Pablo Romero Medinilla.
