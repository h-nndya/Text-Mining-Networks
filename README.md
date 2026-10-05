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

Text-Mining-Analysis/
│
├── Text_Mining_Analysis.Rmd
├── README.md
├── .gitignore
├── Text-Mining-Analysis.Rproj
│
└── CorpusAbstracts/
    └── [user-provided .txt files such as: ]
    └── [book1.txt]
    └── [book2.txt]
    └── [sports1.txt]
    └── [sports2.txt]
