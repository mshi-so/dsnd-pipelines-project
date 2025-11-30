# Predicting whether if a Customer will Recommend StyleSense

## Summary

StyleSense is a rapidly growing online women's clothing retailer. With the customer base exploding in recent months, our Customer Service team cannot keep up with the reviews left on our website to understand whether if a customer will recommend our brand to others, especially for the reviews that are not explicitly saying that.

As a data scientist, I'll build a machine learning model to predict (label) whether if a customer will reccommend based on the data we have collected.

## Getting Started

To start, I have a dataset with 18,000+ records on these features:
Clothing ID
- Age
- Title (Review)
- Review Text
- Positive Feedback Count
- Devision Name
- Department Name
- Class Name
- Reccomend IND

The **Reccomend ID** column contains the data that was previously labeled for whether if a customer will reccomend.

## Libraries Used

Beyond the common python libraries for data science like: pandas, numpy, matplotlib, seaborn, since this dataset contains numerical, categorical and text values, I will be also employing these libraries:
- Pipeline to create preprocessing pipelines
- SimpleImputer to fill in empty values
- MinMaxScaler to normalize numeric values
- OneHotEncorder for categorical values
- SpaCy for lemmatization and tokenization
- TfidfVectorizer for vectorizing text values
- ColumnTransformer to apply preprocssing steps to columns
- RandomForestClassifier for classification model
- RandomizedSearchCV to evaluate and fine-tune the model to get the best fit

## Resources

Git repository for this project is located here: https://github.com/mshi-so/dsnd-course2.git

You can clone this project:

```
git clone https://github.com/mshi-so/dsnd-course2.git
```

## License

[License](LICENSE.txt)
