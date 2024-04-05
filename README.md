## Bankruptcy Prediction 


### Project/Goals

Predicting bankruptcy and measuring financial distress are critical tasks with significant implications for various stakeholders. 
These endeavors hold significant importance for creditors and investors alike, providing them with insights into the likelihood of a firm facing financial insolvency.

### Dataset

This dataset is originally from Emerging Markets Information Service and was downloaded 
[here](https://archive.ics.uci.edu/ml/datasets/Polish+companies+bankruptcy+data).

The Polish dataset poses a significant challenge due to its highly imbalanced nature, where instances of bankrupt companies are vastly outnumbered by non-bankrupt ones. 
To address this imbalance and ensure the robustness of our predictive models, we have implemented three oversampling techniques.


### Project Summary

The objective of financial distress prediction is to construct a predictive model that amalgamates diverse econometric parameters, enabling the anticipation of a firm's financial condition. Throughout this project, our aim is to meticulously document our observations as we delve into the exploration, construction, and comparison of various widely-used classification models.

By embarking on this journey, we achieved several key objectives:

* Comprehensive Data Exploration: We conducted an in-depth exploration of available data, seeking to understand the underlying patterns, trends, and relationships that could influence a firm's financial health.

* Oversampling Techniques: Three different oversampling techniques were applied for comparison: Synthetic Minority Over-sampling Technique (SMOTE), SMOTEENN, SMOTE_Tomek.

* K-Fold Cross Validation: We have employed K-Fold Cross Validation as our data splitting strategy in this project.
  
* Model Development and Comparison: We developed multiple classification models, leveraging state-of-the-art techniques from machine learning and econometrics.
  
    - These models include decision trees, support vector machines, and neural networks.
  
    - Through rigorous experimentation and evaluation to identify the most effective model(s) for predicting financial distress.

* Evaluation Metrics and Validation: We employed a comprehensive suite of evaluation metrics to assess the performance of our models. These metrics include accuracy, precision, recall, F1-score. 


### Recommendation and Conclussion

* The application of different data balancing techniques and data imputation methods yielded notable effects throughout our analysis.
  We observed substantial improvements in model performance and robustness, underscoring the importance of addressing data imbalance and missing values effectively in our predictive modeling pipeline.


* In future iterations of our project, we intend to explore additional strategies to enhance the preprocessing phase further.
  One key area of focus will be the implementation of dimensionality reduction techniques to streamline the dataset and improve computational efficiency.

* Moreover, we plan to extend our analysis by experimenting with a broader array of data imputation and balancing techniques.
* While our initial exploration yielded promising results, there may exist alternative methods that offer superior performance or are better suited to the specific characteristics of our dataset. 
