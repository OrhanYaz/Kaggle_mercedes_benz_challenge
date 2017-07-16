# Kaggle_mercedes_benz_challenge

![](http://www.mercedes-benz.co.uk/content/media_library/hq/hq_mpc_reference_site/passenger_cars_ng/new_cars/amg/12-2013/about_amg/development/mercedes-benz_amg_aboutamg_Entwicklung_buehnenbild_01_740x295_12-2013_jpg.object-Single-MEDIA.tmp/mercedes-benz_amg_aboutamg_Entwicklung_buehnenbild_01_740x295_12-2013.jpg)

https://www.kaggle.com/c/mercedes-benz-greener-manufacturing

## Description
Since the first automobile, the Benz Patent Motor Car in 1886, Mercedes-Benz has stood for important automotive innovations. These include, for example, the passenger safety cell with crumple zone, the airbag and intelligent assistance systems. Mercedes-Benz applies for nearly 2000 patents per year, making the brand the European leader among premium car makers. Daimler’s Mercedes-Benz cars are leaders in the premium car industry. With a huge selection of features and options, customers can choose the customized Mercedes-Benz of their dreams. .

To ensure the safety and reliability of each and every unique car configuration before they hit the road, Daimler’s engineers have developed a robust testing system. But, optimizing the speed of their testing system for so many possible feature combinations is complex and time-consuming without a powerful algorithmic approach. As one of the world’s biggest manufacturers of premium cars, safety and efficiency are paramount on Daimler’s production lines.

In this competition, Daimler is challenging Kagglers to tackle the curse of dimensionality and reduce the time that cars spend on the test bench. Competitors will work with a dataset representing different permutations of Mercedes-Benz car features to predict the time it takes to pass testing. Winning algorithms will contribute to speedier testing, resulting in lower carbon dioxide emissions without reducing Daimler’s standards.

## Codes
<li>https://www.kaggle.com/c/quora-question-pairs/discussion/34355</li>
<li>https://github.com/mpearmain/merc/blob/master/src/datasets/build_datasetV1.py</li>
<li>https://github.com/leexa90/Mercedes-Benz-Greener-Manufacturing</li>
<li>https://github.com/kcrandall/Kaggle_Mercedes_Manufacturing</li>
<li>https://github.com/CuriousAI/ladder</li>

## Methodes

Tpot tutorial:
https://rhiever.github.io/tpot/using/ ou https://github.com/rhiever/tpot.git

Stacking complete guide:
  https://mlwave.com/kaggle-ensembling-guide/

## Results

model | Public LB | Date | Script
--- | --- | --- | ---
Xgboost ICA PCA TSVD GRP SRP Stack Optimisation | 0.57323 | 24th June 2017 | [Optimized_stacked_method](https://github.com/OrhanYaz/Kaggle_mercedes_benz_challenge/blob/master/Optimized_stacked_method.py)
Xgboost ICA PCA TSVD GRP SRP Stack | 0.57066 | 12th June 2017 | [Stacked_method](https://github.com/OrhanYaz/Kaggle_mercedes_benz_challenge/blob/master/Stacked_method.py)
Xgboost ICA PCA TSVD GRP SRP | 0.56784 | 10th June 2017 | [Basic_XGBoost](https://github.com/OrhanYaz/Kaggle_mercedes_benz_challenge/blob/master/script_056784.py)

## Private Leader Board

#### Score: 0.55388

#### Ranking: 13/3835
