# How differently are men and women cited in Swiss media?



## Abstract:
This repository corresponds to the project we did in the context of the EPFL course "Social and Human Sciences: Critical Data Studies", which we conducted in collaboration with Titus Plattner and Paul Ronga.

The goal of the project was to study the distribution/possible disparities in the proportion and the way men and women were cited in Swiss newspapers - more precisely, our analysis was conducted on more than 8000 articles from [Tribune de Genève](https://www.tdg.ch/) and [24 heures](https://www.24heures.ch/) .

## Questions we asked ourselves: 
The main questions that motivated us during this project were the following in no particular order of importance or processing:

- Q1 : How different is the number of men and women cited in Swiss media?

- Q2 : How different were the complexities of the quotes per gender?

- Q3 : What topics are dominated by each gender? Does this have any deeper meaning?

- Q4 : When being quoted, what verbs are used to introduce the quotation by gender? Is one gender more emotive than another, is the other more neutral?

## Methods:

  - #### Quote extraction : 
    The code used to extract the quotes from the articles uses syntactic rules in order to find the quotes. It can find both direct and indirect quotes, extract the quote's author and their gender. It uses a runtime-fixed list of verbs to find them whenever they are used as a way to introduce a quote.

  - #### Topic modelling : 
    The code used to cluster the articles and citations into topics uses multiple embedding methods (one is camemBERT), reduces the dimensionality of the embeddings using UMAP, and finally clusters the topics using either HDBSCAN or k-means to cluster the embeddings into topics.
## Repository content:

**Folders:** 

- `Code` : contains all jupyter notebooks and `.py` files used during analysis
- `Data` : contains the data (processed or not) about the articles
- `img` : contains the plots used in the report due to Tamedia
- `quote_extractor`: contains part of the code used by [Gendered News](https://github.com/getalp/genderednews), more specifically the code related to the extraction of quotes from french texts.

## Required packages:

- bertopic  0.10.0
- Pandas 1.4.2
- numpy 1.21.5
- matplotlib 3.5.0
- seaborn 0.11.2
- transformers 4.11.3
- sklearn 1.0.1
- plotly 
## Authors 
@AttiaYoussef

@unesmu

@TitouMrs

@Majdoulineait

@TorgemanTarak
