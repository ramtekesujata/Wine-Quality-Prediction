# wine_quality_prediction
This project was the part of Winter in Data Science Bootcamp. Data was picked from the internet and it had two subset of data, white wine and red wine. Each data had 12 features, one of which was quality of wine. We were supposed to predict the quality of wine based on remaining 11 features.
Exploratory Data Analysis was performed using pandas and numpy libraries of python, where null values, data size,etc was taken care of.
Used Matplotlib and seaborn to plot and visualize the data effectively and heatmap was plotted.
After performing EDA ,to prepare for predictive analysis for applying ML algorithms, input features were normalized .
Using scikit-learn, data was splitted into parts, one training set and other testing set. ML algorithms were applied to train the training set and to evaluate the model performance, test set is used
since it is multi-class classification problem, multinomial logistic regression, decision trees, random forest, support vector machine, Naive Bayes Classifier, and multi layer perceptron(neural network) and KNN models were trained using mostly scikit packages.
Maximum accuracy was obtained for random forest algorithm .It was almost 65% for both the data sets.(red and white wine)
