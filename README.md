# predicting yelp's elite 
A project to predict a Yelp user's elite status based on user activity, popularity/social network size, review sentiment/content, and review structure. Investigates various classification models, including random forest classifiers, naive bayes, logistic regression, and SVM. Final model achieves an accuracy score of 98% and AUC of 99%. 

For more information, see [my blog post](http://dianalam.github.io/2016/02/28/yelp-classification.html).

## in this repo
* `yelp-text-processing.ipynb` jupyter notebook with scripts and outputs for processing review text
* `yelp-classification.ipynb` jupyter notebook with scripts and outputs for feature engineering and model selection
* `d3/` contains scripts for feature importance bar chart and network graph viz
* `presentation/` contains pdf presentation of findings & recommendations

For the sake of not overloading github, the original data was not uploaded to this repo. Yelp data can be accessed at the link provided at the bottom. 

## installation
### clone this repo  
```bash
$ git clone https://github.com/dianalam/yelp-classifier.git
```

### dependencies
Scripts were written in Python 2.7. You'll need the following modules: 
```bash
matplotlib >= 1.5.1  
numpy >= 1.10.1  
pandas >= 0.17.1  
python-dateutil >= 2.4.2
scipy >= 0.16.0
seaborn >= 0.6.0
sklearn >= 0.17
statsmodels >= 0.6.1
```

To install modules, run:  
```bash
$ pip install <module>
```

### running
To open jupyter notebooks:
```bash
jupyter notebook 
```

To run visualizations:
```bash
python -m SimpleHTTPServer
```
Then navigate to instantiated port. 

## data sources
Thanks to: 
* [Yelp Dataset Challenge](https://www.yelp.com/dataset_challenge)
