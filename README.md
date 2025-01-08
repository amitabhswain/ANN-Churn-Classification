# Customer Churn Prediction using Artificial Neural Networks

A deep learning solution that predicts whether a bank customer is likely to leave the bank (churn) based on various customer attributes. The model is trained using TensorFlow/Keras and deployed as an interactive web application.

Try the model in action: [Customer Churn Predictor](https://ann-churn-classification-nrrft9pympazwcbd9wfd4z.streamlit.app/)

**Project Overview** :- 

This project implements a binary classification model using artificial neural networks to predict customer churn based on historical banking data. The model analyzes various customer attributes including credit score, geography, gender, age, and account details to predict the likelihood of customer attrition.

**Model Architecture** :-

• Input layer handling customer features
• Multiple dense hidden layers with ReLU activation
• Dropout layers for regularization
• Output layer with sigmoid activation
• Early stopping callback to prevent overfitting
• Model monitoring with TensorBoard

**Features** :-

• Real-time predictions through web interface
• Data preprocessing pipeline
• Model performance visualization
• Automated early stopping
• Scalable deployment architecture

**Technical Stack** :-

• TensorFlow/Keras for deep learning
• Streamlit for web interface
• Scikit-learn for data preprocessing
• Pandas for data manipulation
• Pickle for model serialization
• TensorBoard for visualization

**Input Features** :-

• Credit Score
• Geography (France, Spain, Germany)
• Gender
• Age
• Tenure
• Balance
• Number of Products
• Has Credit Card
• Is Active Member
• Estimated Salary

**Project Structure** :-

├── app.py                    # Streamlit web application
├── model.h5                  # Trained neural network model
├── requirements.txt          # Project dependencies
├── label_encoder.pickle      # Label encoder for categorical variables
├── onehot_encoder.pickle    # One-hot encoder for geography
└── scaler.pickle            # Standard scaler for numerical features

**Setup and Installation** :-

• Clone the repository
• Install dependencies: pip install -r requirements.txt
• Run the application: streamlit run app.py

**Model Performance** :-

• Binary classification with cross-entropy loss
• Adam optimizer with learning rate optimization
• Early stopping to prevent overfitting
• Performance monitoring through TensorBoard

This project demonstrates an end-to-end machine learning implementation from data preprocessing to model deployment in a production environment.
