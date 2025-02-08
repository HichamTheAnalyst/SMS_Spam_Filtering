# **Spam Detection Using Machine Learning**  
## **Overview**  
This project applies **machine learning** techniques to detect spam messages using **TF-IDF vectorization** and different classification models. The goal is to classify messages as either **ham (non-spam)** or **spam** based on their textual content.  

## **Dataset**  
- The dataset contains labeled messages categorized as **ham** (legitimate) or **spam** (unwanted).  
- The text is preprocessed and transformed into numerical features using **TF-IDF vectorization**.  

## **Technologies Used**  
- **Python**  
- **Scikit-learn** (Machine Learning)  
- **Pandas** (Data Handling)  
- **NumPy** (Numerical Computing)  
- **NLTK** (Text Processing)  

## **Machine Learning Models**  
Two models were tested and compared:  
1. **Logistic Regression**  
   - Accuracy: **91.83%**  
   - Spam Recall: **40%** (Many spam messages were misclassified as ham)  
2. **Random Forest Classifier** *(Best Model)*  
   - Accuracy: **96.05%**  
   - Spam Recall: **70%** (Better detection of spam)  

## **Preprocessing Steps**  
- **Text Cleaning** (removal of stop words, punctuation, etc.)  
- **TF-IDF Vectorization** (converting text to numerical format)  
- **Splitting Data** into training (80%) and testing (20%)  

## **Model Evaluation**  
- **Precision, Recall, and F1-score** to measure performance  
- **Confusion Matrix** to analyze classification errors  

## **Results**  
| Model | Accuracy | Spam Recall | Spam Precision | F1-score (Spam) |  
|--------|----------|------------|---------------|----------------|  
| Logistic Regression | 91.83% | 40% | 98% | 56% |  
| Random Forest | 96.05% | 70% | 100% | 83% |  
 
