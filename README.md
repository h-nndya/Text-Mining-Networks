# Customisable Text Mining Network Analysis

A customisable text-mining workflow for identifying and visualising
similar themes across document collections.

## Overview

This project uses text mining and network analysis to identify
relationships between themes across a collection of documents. Initially a 
university project with specific abstracts, amended to become applicable to 
other corpora.

## Features

- Text preprocessing and cleaning
- Document-term matrix construction 
- Similarity/network analysis using hierarchical clustering 
- Statistical hypthesis testing and visualisations
- Sentiment Analysis
- Theme identification using cluster algorithms
- Visualisation of relationships between documents/themes using bipartite graphs

## Customisation

Users can provide their own collection of `.txt` documents to create
a custom corpus for analysis with customisable number of pre-determined themes.

## Requirements

- R
- RStudio recommended
- R packages:
  - tm
  - slam
  - SnowballC
  - proxy
  - SentimentAnalysis
  - igraph
  
## Project Structure

CorpusAbstracts/ is excluded from version control. 
Add your own .txt documents to this folder before running the analysis. 
File names should follow the format groupname1.txt, groupname2.txt, etc., 
so that document groups can be identified automatically.
```
Text-Mining-Analysis/
│
├── Text_Mining_Analysis.Rmd
├── README.md
├── .gitignore
├── Text-Mining-Analysis.Rproj
│
└── CorpusAbstracts/
    ├── book1.txt
    ├── book2.txt
    ├── sports1.txt
    ├── sports2.txt
    └── ...your .txt files
```
