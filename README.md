# Hospital-Mortality-prediction

Hospital Mortality is a serious topic which is a life and death event thus in this project I am studying the hospital data and patient information to predict hosiptal mortality. The dataset is highly imbalanced with the target class distribution shown below:

![classImb](https://user-images.githubusercontent.com/51110015/113250728-0c57ee80-928f-11eb-980b-9997c5f64be3.PNG)

I have perform the initial steps of Data Cleaning, Data I am using two standard baseline models to observe the model performance with the unbalanced dataset which we observed in the previous plot. Our aim is the predict whether patient dies or survives in the hospital from the models:

- Logistic Regression
- Random Forest

![LR](https://user-images.githubusercontent.com/51110015/113250881-550fa780-928f-11eb-9346-bbbe7e592902.PNG)

![RF](https://user-images.githubusercontent.com/51110015/113250884-550fa780-928f-11eb-8128-82c0839d2302.PNG)


Over Sampling

I further tried oversampling technique to handle the data imbalance. I am using SMOTE for oversampling. SMOTE(Synthetic Minority Oversampling Technique) is the most widely used approach to synthesizing new examples. SMOTE works by selecting examples that are close in the feature space, drawing a line between the examples in the feature space and drawing a new sample at a point along that line. Synthetic over-sampling works to cause the classifier to build larger decision regions that contain nearby minority class points.

I got the following results:

![LR_smote](https://user-images.githubusercontent.com/51110015/113252059-50e48980-9291-11eb-826d-c7490ee4e238.PNG)

![RF_Smote](https://user-images.githubusercontent.com/51110015/113252060-50e48980-9291-11eb-8cbb-735b7ca2a262.PNG)
