# Kidney-stone-prediction
 In this study, an automated detection of kidney stones using coronal computed tomography (CT) images was proposed with deep learning (DL) technique which has made significant progress in the field of artificial intelligence. A total of 17999 images were used by taking different cross-sectional CT images for each person. Our developed automated model showed an accuracy of 66.67% using Decision Tree in detecting the kidney stones but working on it would produced atleast 85.89% accuracy using Random Forest.
The dataset incorporates six numerical features, namely gravity, pH, osmolality (osmo), conductivity (cond), urea, and calcium (calc). These features are crucial in determining the likelihood of the presence of kidney stones.
To gain insights into the dataset, a set of visualizations have been generated using seaborn and matplotlib. These visualizations provide a clear overview of the distribution and potential outliers within each numerical variable, aiding in the understanding of the data's characteristics.

Decision Tree Classifier
The project employs a Decision Tree Classifier to make predictions. After training the model, evaluation metrics such as Accuracy Score, F-1 Score, Precision Score, Recall Score, Jaccard Score, and Log Loss are computed. These metrics provide a comprehensive assessment of the model's performance on the test data.

Random Forest Classifier
A Random Forest Classifier is also employed in the project. Similar to the Decision Tree Classifier, the model is trained, predictions are made, and performance metrics are calculated. The Random Forest Classifier often exhibits enhanced predictive capabilities compared to a single decision tree.

Logistic Regression
Logistic Regression, a well-known classification algorithm, is included in the project. The model is trained and evaluated using the same set of performance metrics. Logistic Regression is valuable for understanding the relationship between the features and the likelihood of kidney stone presence.
