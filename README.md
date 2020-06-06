# Semantic Score Calculation using Product Reviews
This project focuses on estimating and analyzing the usability scores of the product reviews.
The usability score will be calculated based on different semantic scores like: Subjectivity, Polarity, Flesch index, entropy, Dale Chall index, Lex diversity, etc.

For this project, dataset used is obtained from Julian McAuley’s Amazon Product Reviews dataset.
The link for all Amazon Prodcts reviews is: http://jmcauley.ucsd.edu/data/amazon/
However, this dataset is too large and thus, only a subset from it is actually used in this project.
This project uses a subset from Amazon Product Reviews dataset and subset contains reviews for Toys and Games category products only. 
This subset data is available at link: http://snap.stanford.edu/data/amazon/productGraph/categoryFiles/reviews_Toys_and_Games_5.json.gz

The JSON file is obtained by downloading from this link and unzipped version is used for step 'a' of the code (data conversion from json to csv).
From step 'b' onwards, CSV file obtained by conversion from step 'a' is used. For reference, the csv file is provided in the Data folder of this repository.


To run this project, follow these:
1. Download and unzip the json file from link given above.
2. Keep json file and all source codes in one folder on Google Colab or Jupyter notebook
3. Run all source codes(in folder 'code') in the sequence given below:
    a. DataConversion.ipynb
    b. DataVisualization.ipynb
    c. Pre-processing.ipynb
    d. SemanticScore_Subjectivity.ipynb
    e. SemanticScore_Flesch_Index.ipynb
    f. SemanticScore_Polarity.ipynb
    g. SemanticScore_Entropy.ipynb
    h. SemanticScore_DaleChall_Index.ipynb	
    i. SemanticScore_Helpful_ratio.ipynb
    j. SemanticScore_LexDiversityRatio.ipynb
 4. Run all source codes(in sub-folder 'Semantic scores analysis') in the sequence given below:
    a. Visualize_Score_Subjectivity.ipynb
    b. Visualize_Score_Flesch_index.ipynb
    c. Visualize_Score_Polarity.ipynb
    d. Visualize_Score_Entropy.ipynb
    e. Visualize_Score_Dale_Chall_Index.ipynb
    f. Visualize_Score_Helpful_ratio.ipynb
    g. Visualize_LexDiversity.ipynb
 5. Run all source codes(in folder 'Code') in the sequence given below:
    a. Normalization_Subjectivity.ipynb
    b. Normalization_Flesch_Index.ipynb
    c. Normalization_Polarity.ipynb
    d. Normalization_Entropy.ipynb
    e. Normalization_Dale_Chall_Index.ipynb
    f. Normalization_Helpful_ratio.ipynb
    g. Normalization_LexDiversity.ipynb
 6. Run these source codes(in folder 'Code' and in sub-folder 'Semantic scores analysis') in the sequence given below:
    a. Final_Score_Usability.ipynb
    b. Visualize_Score_Usability.ipynb
