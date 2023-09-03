### Training a model that detects customer reviews as negative or positive
**Datasets:** *bookReviewsData* includes 2 features:
- *Review*: The text content of customer reviews.
- *Positive Review*: A boolean value that appears **True** if the review is determined as a positive review and vice versa.
**Objective:** Creating a model that predicts whether the review is positive or not with a high accuracy of about 80%.
**Purpose:** This helps businesses to better understand customer feedback about their products or services to meet customers' satisfaction and increase the company's revenue.
**Models:** To make the text reviews understandable for the model to learn by using the technique TF-IDF to transfer the text into numerical features. This problem is defined as a binary classification model.
**Libraries**:
- Pandas
- NumPy
- Matplotlib
- Seaborn
**Evaluation metrics**:
- Precision: measure the proportion of correct predicted positive reviews out of all predicted positive reviews.
- Recall: measure the proportion of correct predicted positive reviews out of all actual positive reviews.
**Techniques**:
- Check for missing values within the dataset.
- Visualize class imbalance between positive reviews and negative reviews.
- Splitting the dataset into training and testing sets.
- Using *Random Forest* classification to handle non-linear relationships.
- Test different methods to reach better accuracy by:
  _ Cross-validation.
  _ Grid search CV.
    
  
  

