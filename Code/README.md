## Folder description

This folder contains the python notebooks and scripts containing our different analysis on the articles and citations contained in the Data folder.

## Folder organization : 

### Preprocessing
- `Articles preprocessing.ipynb` : processes the given articles to make them usable, mainly by parsing the sometimes HTML text given as article text to a readable (and usable) format
- `Articles_&_citations_to_dataframe.ipynb` : return a dataframe containing all the citations and articles from the .txt files that were output by  applying GenderedNews to our corpus
### Analysis

- `Topic_modelling.ipynb` : contains the code to group the articles and/or quotes into categories (topics)
- `Topic_modelling_analyses.ipynb` : focus on the quotes from one of the topics extracted from the `Topic_modelling.ipynb` notebook
- `verbes_de_paroles.ipynb` : extracts the verbs introducing the quote (ex: Jean a dit : "...")
- `proportion_homme_femme_in_long_texts.ipynb`: computes the proportion of men and women limiting ourselves to long texts, to see if there is more parity in these.
- 
### Other
- `Manual check GenderedNews performance.ipynb`: checks the performance of the quote extractor form Gendered news, based on the manual annotation of around 100 articles
  <!-- **Scripts :**   **Other :**  --> 

