# Churn Prediction Model

## Introduction
Customer churn is a critical issue for businesses, as it directly impacts revenue and growth. This project implements a churn prediction model using an artificial neural network (ANN) to predict the likelihood of a customer churning based on various input features. By identifying customers at risk of leaving, businesses can take proactive measures to improve retention.

## Model Overview
The churn prediction model is built using TensorFlow and is trained on historical customer data. The model architecture consists of multiple layers, including input, hidden, and output layers. The model is trained using a dataset that includes features such as customer demographics, account information, and transaction history. Performance metrics such as accuracy, precision, and recall are used to evaluate the model's effectiveness.

## Technologies Used
- **Streamlit**: For building the web application interface.
- **TensorFlow**: For creating and training the neural network model.
- **scikit-learn**: For preprocessing data and encoding categorical variables.
- **pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.

## Installation Instructions
To set up the project locally, follow these steps:
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd annclassification
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage Instructions
To run the Streamlit application, use the following command:
```bash
streamlit run app.py
```
Once the application is running, you can input the following features to get predictions:
- **Geography**: Select the customer's geography.
- **Gender**: Select the customer's gender.
- **Age**: Enter the customer's age.
- **Balance**: Enter the customer's account balance.
- **Credit Score**: Enter the customer's credit score.
- **Estimated Salary**: Enter the customer's estimated salary.
- **Tenure**: Select the number of years the customer has been with the bank.
- **Number of Products**: Select the number of products the customer has.
- **Has Credit Card**: Select whether the customer has a credit card.
- **Is Active Member**: Select whether the customer is an active member.

After entering the information, the application will display the predicted churn probability and indicate whether the customer is likely to churn.

## Streamlit Web Link
You can access the deployed Streamlit application at the following link: [Churn Prediction Model](https://churnpredictionmodel.streamlit.app/)

## Future Work
- Explore additional features that could improve the model's accuracy.
- Implement a feedback loop to continuously update the model with new data.
- Develop a dashboard to visualize customer churn trends and insights.

## Conclusion
This churn prediction model serves as a valuable tool for businesses to identify customers at risk of leaving. By leveraging predictive analytics, companies can enhance customer retention strategies and drive growth.
