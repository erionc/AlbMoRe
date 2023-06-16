# AlbMoRe

This repository contains Python code for reproducing the experiments with movie reviews in Albanian. AlbMoRe is a sentiment analysis corpus of movie reviews in Albanian, consisting of 800 records in CSV format. Each record includes a text review retrieved from IMDb and translated in Albanian by the author. It also contains a 0 (negative) or 1 (positive) label added by the author. The corpus is fully balanced, consisting of 400 positive and 400 negative reviews about 67 movies of different genres. From the total of 800 records, 600 of them should be used for model training and development (file train.csv) and the remaining 200 (file
test.csv) should be used for model testing. More details about the creation and the contents of CSRCZ dataset can be found in this [paper](https://arxiv.org/abs/2306.08526).   


## Data

Please download [AlbMoRe corpus](http://hdl.handle.net/11234/1-5165) and place the two files train.csv and test.csv inside the data/ folder. Afterwards, you can run the code of this repository using the following command 

```
$ python basic_experiments.py -c <classifier>
```


## Citation

**If using the AlbMoRe data or the code of this repository, please cite the following paper:**

Erion Çano. AlbMoRe: A Corpus of Movie Reviews for Sentiment Analysis in Albanian. 
CoRR, abs/2306.08526, June 2023. URL https://arxiv.org/abs/2306.08526.

@article{DBLP:journals/corr/abs-2306-08526, \
author = {Erion {\c{C}}ano}, \
title = {AlbMoRe: A Corpus of Movie Reviews for Sentiment Analysis in Albanian}, \
journal = {CoRR}, \
volume = {abs/2306.08526}, \
year = {2023}, \
url = {https://arxiv.org/abs/2306.08526}, \
archivePrefix = {arXiv}, \
eprint = {2306.08526}, \
}
