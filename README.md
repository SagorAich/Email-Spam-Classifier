"# Email-Spam-Classifier" 

Steps:
1. Prepare notebook
2. Create .pkl files
3. Streamlit to make a website
4. Render for deployment


About the files:
1. Dataset used: https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset
2. Dataset zip: archive.zip
3. Dataset unzip: spam.csv
4. Notebook of the task: Email_Spam_Classifier.ipynb
5. Trained model file: model.pkl
6. Vectorizer file: vectorizer.pkl
7. Streamlit files: Procfile, app.py, nltk.txt, requirements.txt, setup.sh


Steps used for making the notebook:
1. Data loading
2. Exploratory Data Analysis (EDA)
3. Data Preprocessing
    Lower case  
    Tokenization  
    Removing special characters  
    Removing stop words and punctuation  
    Stemming  
4. Model Building (Model used for this task)
   LogisticRegression
   SVC
   MultinomialNB
   DecisionTreeClassifier
   KNeighborsClassifier
   RandomForestClassifier
   AdaBoostClassifier
   BaggingClassifier
   ExtraTreesClassifier
   GradientBoostingClassifier
   XGBClassifier
5. Model Selection: This dataset is imbalanced, containing 4516 samples for class 0 and 653 samples for class 1. That's why I had to focus more on the 'precision' value than accuracy. Generally, Multinomial Naive Bayes shows good results for textual data; also, here Multinomial Naive Bayes gives the best result than other algorithms. For this, I have imported Multinomial Naive Bayes in the model.pkl file.


