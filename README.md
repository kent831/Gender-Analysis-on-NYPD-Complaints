# Gender-Analysis-on-NYPD-Complaints
**By: Kent Utama, Lauren Sidarto**

## Introduction
The report below uses the "Civilian Complaints Against New York City Police Officers" dataset, published by the New York City’s Civilian Complaint Review Board. The dataset contains more than 12,000 civilian complaints filed against New York City police officers; to be specific, these are records of closed cases for every police officer still on the force as of late June 2020.

The dataset contains details such as:

- The officers' details (shield number, rank, race, etc.)
- The complainants' details (age, race, gender, etc.)
- Category describing the alleged misconduct,
- The Civilian Complaint Review Board's (CCRB) conclusion on whether officers' conducts violated NYPD rules

There has been a recent upswing of movements supporting feminism over recent years, and it is still a pertinent issue covered on the news. With this information in mind, we would like to investigate whether or not the Civilian Complaint Review Board (CCRB) is biased towards men. That is, if complaints from women have a lower success rate (substantiated or exonerated) than that of men's.

Following this, we would then build a classifier where we get a few features and predict whether the outcome of a complaint ends up succesful (substantiated or exonerated) or not (unsubstantiated). We would like to find out how our classifier would emphasis weight on the features, especially gender. Lastly, we also tested on whether our model is fair or not on males vs females. In order to do this, we used precision (i.e. true positives) as our evaluation metric since it allows us to know how much of the actually successful outcomes were we able to correctly predict.

## Process
Throughout the project, we:
1. Addressed missing data
2. Did a permutation test to find out the difference in successful complaints between men and women
3. Made a baseline model using Logistic Regression
4. Made a final model with more engineered features using Logistic Regression
5. Evaluated fairness with precision

## Conclusion
To conclude the project, we found that women have an advantage when it comes to filing complaints towards the NYPD. Based on our model, this advantage is up by 2% when compared to men's. Although our findings show that men and women are not treated differently in 2019, the history regarding gender roles cannot be denied. Thus, a future project that can be derived from this is a model strictly made on some years instead of overtime. This can even be extended to a time series analysis to show the true change in favoritism/sexism in the NYPD over the past century.

We found that society has made big steps toward fairness for both men and women. Although this disparity can still be felt in a lot of aspects in life, this project is a mere sign that this disparity is slowly diminishing.

**Note: A detailed summary of findings is present in the notebook**
