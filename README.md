# Analyzing 10Gb of Yelp Reviews Data

We will analyze a subset of Yelp's business, reviews and user data. This dataset comes to us from [Kaggle](https://www.kaggle.com/yelp-dataset/yelp-dataset) although we have taken steps to pull this data into a publis s3 bucket: `s3://sta9760-yelpdataset/yelp-light/*business.json`

## [Analysis](Analysis.ipynb)

Note that the output of the code written is provided as a means to give you structure as you write your analysis. For **Parts I, II & III**, you must fill in the blanks (however way you want) to get the output provided in the file. (Mainly columns and aggregations, I don't care about the exact rows). For **Parts III and IV**, you are more flexibility to take the analysis further however you see fit.

I finished all questions. For the last question, I analysis the 'skew' of stars from elite users and actual stars. I found no significant biases between the elite users's review and actual review, thus the elite users could be trusted.

## Cluster and Notebook Configs

![cluster_image](assets/cluster_configuration.png)
![notebook_image](assets/notebook_configuration.png)
