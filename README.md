# Persian News Categorization and Sentiment Analysis Using NLP and ML
****Abstract:****

text classification on Persian text data by comparing different vectorization techniques like TF-IDF and Bag of Words, and evaluating various machine learning models such as SVM, logistic regression, etc. for multi-class classification of categories based on preprocessed title, body and abstract text fields. data ingestion, text preprocessing, vectorization, model training and evaluation using cross-validation, final testing on held-out set, and comparative analysis of model performance using accuracy and F1 score to determine the best approaches for Persian text classification.
####
****Text Cleaning:****
To ensure data quality and consistency, rigorous text cleaning procedures are applied. This included removing special characters, punctuation, and common stopwords. The objective is to prepare the text data for subsequent analysis and modeling.

****Vectorization:****
Text data is transformed into numerical vectors using two prominent techniques: TF-IDF (Term Frequency-Inverse Document Frequency) and Count Vectorization. These techniques convert the textual data from the Persian newspaper case study into a format suitable for machine learning model training.

****Model Training:****
Training and evaluating text classification models are of the primary aims therefore various machine learning algorithms are explored, including Random Forest, Linear SVC, Logistic Regression, Decision Tree, and K-Nearest Neighbors (KNN). Model performance is assessed using accuracy as the primary evaluation metric on both training and testing datasets.


The results indicated that the Logistic Regression model, demonstrated the highest accuracy in categorizing newspaper articles into predefined topics. This achievement highlights the potential of this approach for similar real-world applications in the domain of Persian news or text classification in general.
