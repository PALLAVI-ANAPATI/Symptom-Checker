## Symptom Checker - Suggested Medicine and Diet Recommendation
![imgalt](https://github.com/PALLAVI-ANAPATI/Symptom-Checker/blob/main/image/1.png)
![imgalt](https://github.com/PALLAVI-ANAPATI/Symptom-Checker/blob/main/image/2.png)
---

## Table of Contents
1. [Description](#description)
2. [Methodology](#methodology)
3. [Technology Required](#technology-required)
4. [Usage](#usage)
5. [Conclusion](#conclusion)

## Description
This project is a web-based application built using Flask that provides users with medicine and diet recommendations based on their symptoms. By leveraging machine learning techniques, specifically TF-IDF vectorization and RandomForestClassifier, the system can analyze user input and predict the most relevant treatments. The project includes a dataset of symptoms, corresponding medicines, and recommended diets to provide meaningful suggestions.

A key feature of this system is its ability to handle variations in symptom input using fuzzy matching, ensuring that users receive appropriate recommendations even if they enter slightly different symptom descriptions. This makes the application more robust and user-friendly. The project aims to assist individuals in making informed health decisions while emphasizing that professional medical consultation is still essential for serious conditions.

## Methodology
- Utilizes TF-IDF vectorization for text processing.
- Uses RandomForestClassifier to predict medicine and diet plans.
- Implements fuzzy matching for improved symptom recognition.
- Processes user input and provides recommendations based on trained models.


## Technology Required
- **Programming Language:** Python 3.10 and above
- **Framework:** Flask
- **Machine Learning Libraries:** scikit-learn, pandas
- **Text Processing:** TfidfVectorizer (from scikit-learn)
- **Fuzzy Matching:** fuzzywuzzy
- **Frontend:** HTML, CSS

## Usage
- Download this repository via GIT or zip.
- Open CMD in directory of this repository(Python 3.10 and above should be installed)
- type pip install -r requirements.txt.
- After installation run app.py.
- Go to the 127.0.0.1:5000/chatbot, You can start chatting.

## Conclusion
This project demonstrates a practical approach to symptom-based medical assistance using machine learning. By integrating fuzzy matching and predictive modeling, it offers users a way to receive medicine and diet recommendations efficiently. However, while this system can provide helpful guidance, it is not a replacement for professional medical advice. Future improvements could include a larger dataset, more advanced NLP techniques, and a feedback mechanism to enhance the accuracy of recommendations. 


