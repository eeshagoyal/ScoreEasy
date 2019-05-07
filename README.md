# ScoreEasy :  Automated Essay Scoring

## Brief Overview

The project aims to build a machine learning system for automatic scoring of essays written  by  students. The  motivation for the project comes from  [Kaggle]( https://www.kaggle.com/c/asap-aes). The system takes as input as essay and outputs a score calculated with respect to six rating traits, namely Ideas and Content, Organization, Voice, Word
Choice, Sentence Fluency and  Conventions, rated with respect to the essay set.


## Files Description

The work is distributed in a set of jupyter notebooks.

1. **kaggle-dataset/** : directory consisting of the Dataset, taken from Kaggle. 
   - Training dataset - `training_set_rel3.tsv`
   - Validation dataset - `valid_set.tsv`
   - Testing dataset - `test_set.tsv`
2. **1.1-EDA.ipynb and 1.2-Basic-Metric-Analysis.ipynb**: Initial data analysis of the entire dataset and key findings from the data that would provide for specific parameters in developing the model. 
3. **2-LDA.ipynb**: A brief experiment done to implement an unsupervised approach to assign scores based on word probabilities. 
4. **3-Tokenisation-and-Regression.ipynb**: Tokenisation, feature extraction, application regression techniques (Linear, Lasso, Ridge, Gradient Boosting) and accuracy comparison.
5. **4(a)-LSTM.ipynb, 4(b)-LSTM.ipynb and 4(c)-LSTM.ipynb**: Notebooks implementing the LSTM model to scoring essays.



## Links
- [Overleaf Report](https://www.overleaf.com/read/gcskmvxcfpqm)
- [Overleaf Poster](https://www.overleaf.com/read/dmqgbcvhmrfm)
- [Presentation](https://docs.google.com/presentation/d/1UbnmHWUEYuINp4Go8viGmXapK_t43y812SKYqFJcEBs/edit?usp=sharing)
- [Github Link](https://github.com/eeshagoyal/ScoreEasy)
- [Data Set](https://www.kaggle.com/c/asap-aes)
