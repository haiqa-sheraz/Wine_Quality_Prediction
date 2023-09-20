# Wine_Quality_Prediction
🍷📊 Mastering Wine Quality Prediction: A Journey Through Data Exploration and Machine Learning 🤖

During my enriching Machine Learning internship with TechnoHacks, I had the privilege of working on a fascinating project—predicting wine quality within the range of [3, 4, 5, 6, 7, 8]. Here's a glimpse into my journey:

🔍 **Exploratory Data Analysis (EDA)**
First things first, I ensured our dataset was impeccable with no missing values. Next, I delved into feature correlations to identify which factors influenced wine quality the most. A heatmap visualization using Seaborn unveiled fascinating insights.

📈 **Visualizing the Story**
To understand the nuances, I crafted visualizations. I compared highly correlated variables like alcohol and volatile acidity, unveiling clear trends. Then, I explored features with lower correlations like pH and free sulfur dioxide, bringing out intriguing patterns through scatterplots, lineplots, barplots, and even donut charts to showcase percentages.

📏 **Data Scaling and Splitting**
With insights in hand, I standardized the data using StandardScaler and split it into training and testing sets (with a test size of 0.25) to prepare for model building.

🌲 **Modeling with Random Forest and Decision Trees**
I kicked off the modeling journey with Random Forest, achieving an accuracy of 68.5%. The trusty Decision Tree model followed with an accuracy of 64%.

🧮 **XGBoost and SVM**
To enhance performance, I encoded the target labels using LabelEncoder. The XGBoost model exhibited its prowess with an accuracy of 68%, while the Support Vector Machine (SVM) garnered an accuracy of 60.25%.

🧠 **Building a Neural Network**
Taking a deep dive into deep learning, I designed a Neural Network with dense and dropout layers, employing the Adam optimizer with a learning rate of 0.001. After 300 epochs, the model achieved an accuracy of 71.64% while gracefully balancing the line between learning and overfitting.

🤝 **Ensemble Learning**
For added robustness, I crafted an ensemble model—a VotingClassifier comprising Decision Trees, Random Forest, and SVM. This combined effort yielded an accuracy of 66.5%.

👜 **Bagging Classifier with Random Forest**
Lastly, I leveraged the Bagging Classifier with Random Forest as the base classifier, culminating in an impressive accuracy of 70.25%.

This exhilarating journey through data exploration and machine learning techniques has been a rewarding experience during my internship with TechnoHacks. It reaffirmed my passion for the field and underscored the power of data-driven decision-making. 🚀📈 #MachineLearning #DataScience #WineQualityPrediction #TechnoHacks #Internship #DeepLearning #EnsembleLearning
