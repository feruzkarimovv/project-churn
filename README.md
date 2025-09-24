# Customer Churn Prediction App

A Streamlit application that predicts customer churn using multiple machine learning models and provides AI-powered explanations.

## Features

- **Multi-Model Prediction**: Uses XGBoost, Random Forest, and K-Nearest Neighbors models
- **Interactive UI**: Select customers and modify their attributes
- **AI Explanations**: Powered by Groq API for intelligent prediction explanations
- **Email Generation**: Automatically generates retention emails for at-risk customers

## Deployment

### Streamlit Cloud (Recommended)

1. Fork this repository
2. Go to [share.streamlit.io](https://share.streamlit.io)
3. Connect your GitHub account
4. Select this repository
5. Set the following environment variables:
   - `GROQ_API_KEY`: Your Groq API key
6. Deploy!

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/feruzkarimovv/project-churn.git
cd project-churn
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Set environment variable:
```bash
export GROQ_API_KEY="your_groq_api_key_here"
```

4. Run the application:
```bash
streamlit run main.py
```

## Environment Variables

- `GROQ_API_KEY`: Required for AI explanations and email generation

## Models Used

- XGBoost
- Random Forest
- Decision Tree
- SVM
- K-Nearest Neighbors
- Naive Bayes
- Voting Classifier

## Data

The application uses a customer churn dataset with the following features:
- Credit Score
- Age
- Tenure
- Balance
- Number of Products
- Has Credit Card
- Is Active Member
- Estimated Salary
- Geography
- Gender
