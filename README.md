# Contextualized-Cosine
This repository contains the code related to Apallius de Vos et al. (2021) (link to be added). This research proposed an extended cosine similarity measure. This improves performance on word similarity tasks, with gains in interpretability. This approach seems to be particularly useful when the word-similarity pairs share the same context, for which distinct contextualized similarity measures can be learned. The data this code uses is a combination of the dataset created by Richie et al. (2020), which can be found [here](https://link.springer.com/article/10.3758/s13428-020-01362-y).  Additionally, the [SimLex-999](https://fh295.github.io/simlex.html) data and the [WordSim-353](http://alfonseca.org/eng/research/wordsim353.html) datasets were used to compare results found from the dataset from Richie et al. (2020) with more common datasets when looking at word similarity tasks. 

#### Packages Required
To be able to run this code, the following Python 3 packages must be installed: 


 - `math`
 - `os`
 - `copy`
 - `csv`
 - `re`
 - `scipy`
 - `time`
 - `pandas`
 - `matplotlib`
 - `numpy`
 - `seaborn`
 - `collections`
 - `sklearn`
 - `torch`
 - `transformers`
 - `gensim`
