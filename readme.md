<img src="square-logo.svg" width=200 height=200 align="right">

This repository contains some example components meant for educational/inspirational
purposes. These are components that we open source to encourage experimentation but
these are components that are **not officially supported**. There will be some tests 
as well as some documentation but this project should be considered a community project,
not something that is part of core Rasa. 

# Components 

The following components are implemented. 

### Meta 

- `rasa_nlu_examples.meta.Printer`: a printer that's useful for debugging

### Dense Featurizers 

- `rasa_nlu_examples.featurizers.dense_featurizer.FastTextFeaturizer`: fasttext word embeddings [link](https://fasttext.cc/)
- `rasa_nlu_examples.featurizers.dense_featurizer.BytePairFeaturizer`: pretrained byte-pair word embeddings [link](https://nlp.h-its.org/bpemb/)
