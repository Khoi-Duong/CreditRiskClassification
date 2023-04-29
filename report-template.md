# Module 20 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:

![ClassificationReport Original Data](https://user-images.githubusercontent.com/119692456/235296898-7433c8f8-7e17-4b57-909a-136599a9c104.png)



* Machine Learning Model 2:

![ClassificationReport Resampled Data](https://user-images.githubusercontent.com/119692456/235297017-ae62b8d2-8131-4b7a-b150-3c30e94b86a2.png)


## Summary
Collected data can be effectively used to train and test the Machine Learning Classification Model. In order to generate more precise/accurate predictions, solving the imbalance sampling issue is important

Randomly oversampling the data helps us get a higher balanced accuracy and recall scores. With a higher recall value, the model is able to predict risky loans more accurately.

With incorrect predictions we have two issues:

    -False Positives (where users are flagged as risky, but are actually healthy)

    -False Negatives (where users are not flagged as risky but are actually risky)
    
Both incorrect predictions have negative downsides; as a result, it is important for the model to be as precise and accurate as possible.
