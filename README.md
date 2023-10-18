# **SyriaTel Customer Churn Prediction**

![Customer Churn](https://github.com/frankkiptoo/phase-3-project/assets/133040810/c0f5564e-9d65-4c50-8e42-06818f81a1ae)

---

## **Overview**
The objective of this project is to harness machine learning capabilities to predict the likelihood of customer churn for SyriaTel, a telecommunications company. Through machine learning models, this project aims to provide an actionable roadmap for SyriaTel to optimize their customer retention strategies and boost customer satisfaction.

---

## **Business and Data Understanding**

### **Stakeholder Audience**
The main stakeholder is SyriaTel, a telecommunications company interested in retaining their customers and minimizing financial losses arising from potential churn.

### **Dataset**
Data has been sourced from [Kaggle](https://www.kaggle.com/datasets/becksddf/churn-in-telecoms-dataset). The dataset includes variables such as state, account length, area code, and various call-related metrics. A more detailed look reveals features like international plan, voicemail plan, customer service calls, and churn.

---

## **Modeling**

### **Business Problem**
SyriaTel, being a frontrunner in telecommunications, aims to tackle increasing customer churn rates which translate into significant revenue losses. The focus is to develop an effective model that identifies potential churn and helps the company tailor their strategies accordingly.

### **Methodology**
This project adheres to the CRISP-DM framework, which guides through understanding, preparing, modeling, evaluating, and deploying the solution. Various models will be experimented with, starting with a basic logistic regression model, progressing to more intricate models like Decision Trees. Performance will be measured using metrics such as accuracy, precision, recall, and F1-score.

### **Objectives**
- To create machine learning models that predict customer churn by analyzing SyriaTel's data.
- To compare different models and pinpoint the most effective one for prediction.
- To discover the major factors influencing churn at SyriaTel and provide actionable insights to help reduce these churn rates.

---

## **Evaluation**

### **Model Performance Overview**

- **Logistic Regression**
  * **Precision**: 95.1% (Class 0), 39.0% (Class 1)
  * **Recall**: 77.9% (Class 0), 70.3% (Class 1)
  * **F1-Score**: 85.9% (Class 0), 51.8% (Class 1)
  * **Accuracy**: 78.3%

- **Decision Tree Classifier**
  * **Accuracy**: 90% (Training), 93% (Test)
  * **AUC**: 92.89% (Training), 87.45% (Test)
  * **Precision & Recall**: 96.57% & 94.52% (Class 0), 72.57% & 81.19% (Class 1)

- **Random Forest Model**
  * **Accuracy**: 90.67% (Training), 92.80% (Test)
  * **AUC**: 95.42% (Training), 91.76% (Test)
  * **Precision & Recall**: 97.26% & 94.17% (Class 0), 72.27% & 85.15% (Class 1)

### **Model Evaluation Criteria**
1. **Accuracy**: Proportion of correct predictions.
2. **Generalization**: Model's performance on unseen data.
3. **Consistency**: Stable performance across datasets.
4. **Complexity**: Ability to capture complex data relationships.
5. **Feature Importance**: Identifying significant features for predictions.

![Baseline ROC Curve](https://github.com/frankkiptoo/phase-3-project/assets/133040810/2437b30b-0453-4c6e-952c-d7d861f6b23c)
![CV Logistic Regression ROC Curve](https://github.com/frankkiptoo/phase-3-project/assets/133040810/01f8e72b-7a22-4efe-8485-8f229e0fd966)
![Decision Tree ROC curve](https://github.com/frankkiptoo/phase-3-project/assets/133040810/16fbb60d-8f1f-44c6-bd1d-6b13af92369f)
![Grid Search Random Forest ROC Curve](https://github.com/frankkiptoo/phase-3-project/assets/133040810/38466a8e-cd6e-48e0-affd-bef8fc8ae327)
![Random Forest Model ROC Curve](https://github.com/frankkiptoo/phase-3-project/assets/133040810/cad5faaa-d378-4e60-9dcc-7dce91fc1f0c)

---

## **Conclusion**

After careful analysis and evaluation of the models – Logistic Regression, Decision Tree Classifier, and Random Forest – the Random Forest model emerged as the standout choice for predicting customer churn for SyriaTel. This model not only excels in accuracy, consistency, and complexity but also offers valuable insights through feature importance, making it the best fit for SyriaTel's needs.

SyriaTel, by leveraging the insights from the Random Forest model, can actively address customer churn, efficiently allocate resources, and cultivate enduring customer loyalty. Continuous adaptation and monitoring of the model are pivotal to remain attuned to evolving customer behaviors in the telecom sphere.

![Baseline Model Confusion Matrix](https://github.com/frankkiptoo/phase-3-project/assets/133040810/ec047fe0-7cf4-4633-85b5-d2dfdce5eeba)
![Cross Validation Score Confusion Matrix](https://github.com/frankkiptoo/phase-3-project/assets/133040810/b23e7a6e-24af-4420-b926-c2c50d8488f7)
![Decision Tree Confusion Matrix](https://github.com/frankkiptoo/phase-3-project/assets/133040810/81a60fed-cc45-4daf-b3ea-bb573f2f7820)
![Grid Search Random Model Confusion Matrix](https://github.com/frankkiptoo/phase-3-project/assets/133040810/e534baf9-9a77-4526-9809-a509513a4188)
![Random Forest Confusion Matrix](https://github.com/frankkiptoo/phase-3-project/assets/133040810/05515176-0d8e-4f07-88e0-c4eadf591adc)

---

## **Recommendation**

SyriaTel can harness the full potential of the Random Forest model by:

1. **Leveraging Predictive Insights**: Using model predictions to refine customer retention tactics.
2. **Implementing Personalized Marketing Campaigns**: Designing promotions tailored to individual customer profiles.
3. **Enhancing Customer Service**: Prioritizing improvements in the customer support sector.
4. **Optimizing Pricing and Offerings**: Reassessing call rates and introducing value-added services.
5. **Monitoring and Updating the Model**: Periodically retraining the model with fresh data.
6. **Investing in Customer Feedback Mechanisms**: Garnering direct insights from customers to refine offerings.
7. **Measuring and Evaluating Outcomes**: Setting KPIs and monitoring the impact of retention strategies.

[Insert visualization for recommendations here]

By adopting these recommendations, SyriaTel can fortify its position in the competitive telecom industry, reduce churn rates, and foster a loyal customer base.

---
