# NLP 

## This project was completed using a python notebook to make thing modular as compared to a python script file
### The instructions are as follows:
1.EDA Expansion: <br>
Explore the most common words in fake and real headlines using separate word clouds or bar plots. What patterns can you observe?
 
2.Advanced Text Preprocessing <br>
Modify the preprocessing pipeline to include lemmatization using spaCy or NLTK WordNetLemmatizer. How does lemmatization affect model accuracy?
 
3.Class Imbalance Handling<br>
Simulate class imbalance by undersampling the 'Real' headlines. Then apply SMOTE (or similar) to rebalance. How does balancing affect model performance?
 
4.Hyperparameter Tuning<br>
Use GridSearchCV or RandomizedSearchCV to tune hyperparameters for the Random Forest or SVM model. Which hyperparameters provide the best accuracy?
 
5.Cross-Validation Evaluation<br>
Replace the train/test split with K-Fold cross-validation (e.g., K=5). Report the average accuracy and standard deviation for each model.
 
6.Feature Engineering<br>
Instead of using only TF-IDF, create custom features like headline length, number of capital letters, and punctuation count. Does adding these features improve your model?
 
7.Confusion Matrix Analysis<br>
Visualize confusion matrices for all models side-by-side. Which model makes the most false positives? What are the implications in a real-world fake news detection system?
 
8.Explainable AI (XAI)<br>
Use LIME or SHAP to explain a few predictions from your best-performing model. What keywords contributed to the prediction of 'Fake' or 'Real'?
 
9.Ensemble Modeling<br>
Combine the predictions of Logistic Regression, SVM, and Random Forest using a VotingClassifier. Does ensemble learning outperform the individual models?
 
10.Real-World Testing<br>
Collect 5 real headlines from a news website and 5 fake headlines from a satire site (like The Onion). Use your best model to classify them. Were the predictions accurate?
