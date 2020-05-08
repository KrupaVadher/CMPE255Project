# CMPE255-Project
This project focuses on estimating and analyzing the usability scores of the product reviews.
The usability score will be calculated based on different semantic scores like: Subjectivity, Polarity, Flesch index, entropy, Dale Chall index, Lex diversity, etc.

For this project, dataset used is obtained from Julian McAuley’s Amazon Product Reviews dataset.
The link for all Amazon Prodcts reviews is: http://jmcauley.ucsd.edu/data/amazon/
However, this dataset is too large and thus, only a subset from it is actually used in this project.
This project uses a subset from Amazon Product Reviews dataset and subset contains reviews for Toys and Games category products only. 
This subset data is available at link: http://snap.stanford.edu/data/amazon/productGraph/categoryFiles/reviews_Toys_and_Games_5.json.gz

The JSON file is obtained by downloading from this link and unzipped version is used for step 'a' of the code (data conversion from json to csv).
From step 'b' onwards, CSV file obtained by conversion from step 'a' is used.


To run this project, follow these:
1. Download and unzip the json file from link given above.
2. Keep json file and all source codes in one folder on Google Colab or Jupyter notebook
3. Run all source codes(in folder 'code') in the sequence given below:
    a. DataConversion
    b. DataVisualization
    c. Pre-processing
    d. SemanticScore_Subjectivity
    e. SemanticScore_Flesch_Index
    f. SemanticScore_Polarity
    g. SemanticScore_Entropy
    h. SemanticScore_DaleChall_Index	
    i. SemanticScore_Helpful_ratio
 4. Run all source codes(in sub-folder 'Semantic scores analysis') in the sequence given below:
    a. Visualize_Score_Subjectivity
    b. Visualize_Score_Flesch_index
    c. Visualize_Score_Polarity
    d. Visualize_Score_Entropy
