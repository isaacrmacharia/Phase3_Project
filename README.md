# SyriaTel Customer Churn Prediction

## Project Overview

Customer churn represents a direct revenue risk to the business. This
project aims to predict customer churn early, enabling proactive
retention strategies and more effective resource allocation.

The objective is to build a classification model that identifies
customers who are likely to churn so that targeted interventions can be
implemented before revenue is lost.

------------------------------------------------------------------------

## Business Objective

-   Identify high-risk customers before they churn
-   Enable data-driven retention strategies
-   Reduce revenue loss and operational inefficiencies
-   Support decision-making with measurable performance metrics

------------------------------------------------------------------------

## Dataset Summary

-   Total Test Samples: 667
-   Majority Class (Non-Churn): 570
-   Minority Class (Churn): 97
-   Dataset is imbalanced

------------------------------------------------------------------------

## Model Used

Logistic Regression (baseline model)

------------------------------------------------------------------------

## Evaluation Metrics

Due to class imbalance, multiple metrics were used:

-   **Accuracy** -- Overall correctness of predictions
-   **Precision** -- Quality of churn predictions
-   **Recall** -- Ability to detect churn customers
-   **F1-Score** -- Balance between precision and recall
-   **Confusion Matrix** -- Detailed error analysis

------------------------------------------------------------------------

## Model Performance

-   Accuracy: **85.9%**
-   Churn Recall: **24%**
-   Churn F1-Score: **0.33**

### Key Insight

Although the model shows strong overall accuracy, it performs poorly in
detecting churn customers. Approximately 76% of churn cases go
undetected, limiting its effectiveness for retention strategy
implementation.

------------------------------------------------------------------------

## Business Impact

-   Majority of churn customers go undetected
-   Retention efforts may miss high-risk customers
-   Potential financial and operational impact
-   Model currently biased toward predicting non-churn

------------------------------------------------------------------------

## Recommendations

To improve performance and reduce business risk:

-   Improve detection of at-risk customers
-   Focus on churn identification rather than overall accuracy
-   Explore advanced modeling approaches
-   Optimize evaluation toward recall and balanced performance

------------------------------------------------------------------------

## Conclusion

While the model demonstrates strong headline accuracy (86%), it is not
yet ready for deployment due to weak churn detection capability. Further
refinement is required to enhance predictive performance and support
effective retention strategies.

------------------------------------------------------------------------

## Author

Data Science Project -- Customer Churn Prediction
