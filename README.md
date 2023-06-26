<h2 align="center" style="font-size: 36px;text-decoration:  underline; color: #301E67;">Click Through Rate Prediction Assignment</h2>

Most websites display ads to generate revenue, making the online advertising industry enormous. Industry leaders like Google, Amazon, and Facebook generate billions of dollars by targeting the right audience with relevant ads. Data-driven solutions play a crucial role in making decisions about ad selection, targeting, placement, and optimization.

This repository focuses on the task of Click-Through Rate (CTR) prediction, which helps marketing teams answer key ad placement-related questions. CTR prediction is essential for evaluating ad performance in online advertising and is widely used for sponsored search and real-time bidding.

<h2  style="font-size: 24px; color: #301E67;">Objective</h2>

- How do you know which ad to use and who to target?

- Many companies advertise products in the same category, so how do you decide whose ad to display?

- Which ad should be placed on which part of the web page?

- Should a particular ad be pushed on a mobile device or remain on a desktop or laptop?


The objective of this project is to develop accurate CTR prediction models that can assist in making informed decisions about ad placement. By predicting whether the audience will click on an ad or not, marketing teams can optimize their ad targeting strategies.


<h2  style="font-size: 18px; color: #301E67;">Data Description</h2>

| Variable         | Description                                              |
| ---------------- | -------------------------------------------------------- |
| click            | 0/1 for non-click/click                                  |
| hour             | Format is YYMMDDHH, so 14091123 means 23:00 on Sept. 11, 2014 UTC |
| C1               | Anonymized categorical variable                          |
| banner_pos       | Position of the ad/banner on the page                    |
| site_id          | Unique ID of the site on which the ad is shown           |
| site_domain      | Unique domain of the site on which the ad is shown       |
| site_category    | Category of the site on which the ad is shown            |
| app_id           | App ID of the site on which the ad is shown              |
| app_domain       | App category of the site on which the ad is shown        |
| app_category     | Category ID of the site on which the ad is shown         |
| device_id        | Device ID on which the ad was shown                      |
| device_ip        | IP address of the device on which the ad was shown       |
| device_model     | Model type of the device on which the ad was shown       |
| device_type      | The device type on which the ad was shown                |
| device_conn_type | The connection type of the device on which the ad was shown |
| C14 - C21        | Anonymized categorical variables                         |


<h2  style="font-size: 18px; color: #301E67;">Methodology</h2>
We have implemented various machine learning models for CTR prediction, including Logistic Regression, Decision Trees, and Random Forest. The models have been trained and evaluated on both balanced and imbalanced datasets to assess their performance under different conditions.

<h2  style="font-size: 18px; color: #301E67;">Libraries Used</h2>
- pandas: Data manipulation and analysis
- numpy: Mathematical operations on arrays
- seaborn: Data visualization
- matplotlib.pyplot: Plotting graphs
- warnings: Control warning messages
- sklearn: Machine learning algorithms and evaluation metrics
- imblearn: Handling imbalanced datasets
- statsmodels: Statistical models and analysis
- category_encoders: Encoding categorical features

<h2  style="font-size: 18px; color: #301E67;">Results</h2>
The results obtained from training and evaluating the models are summarized in a table, including accuracy, recall, precision, and cross-validation scores. The performance of each model on both the training and test datasets is presented, along with the mean cross-validation score.

<h2  style="font-size: 18px; color: #301E67;">Usage</h2>
The code provided in this repository can be used as a reference for implementing CTR prediction models in online advertising. The analysis and insights derived from the code can help marketing professionals and data scientists understand the effectiveness of different models and make informed decisions about ad placement.

<h2  style="font-size: 18px; color: #301E67;">Documentation</h2>
Please refer to the code and documentation provided in this repository for detailed implementation details, data preprocessing steps, model training, evaluation, and visualization techniques.



