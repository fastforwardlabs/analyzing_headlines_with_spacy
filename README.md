# Analyzing news headlines with spaCy

[SpaCy](https://spacy.io/) wraps industrial-strength natural language processing capabilites into a Python library with an elegant and powerful API.
The notebook in this repo demonstrates its use for Named Entity Recognition (NER) on a real world news dataset.

![Sentences with named entities highlighted.](images/NER.png)

We take a public domain dataset of [Reuters news headlines](https://www.kaggle.com/notlucasp/financial-news-headlines) and use spaCY to extract named entities.
We demonstrate three example downstream use cases:
- investigating the organisations that appeared most often in Reuters in 2020
- viewing the mentions of any given organisation over time
- inspecting which organisations appear in headlines together

## Instructions

To run the notebook, start a Python 3 Jupyter notebook server.
Library and dependencies are installed inline in the notebook.

Happy hacking!
