#  What is Phising?

- Phishing is an attack type that is organized by faudsters, and it is performed to steal sensitive, personal, and financial information of victims.

- Phishers especially targets communication channels such as: E-mail, SMS, Social Media Platforms, Websites, Payment Pages..
- There are two main concepts to prevent Phishing attacks:
     - User Education
     - Sophisticated Software Systems


- Detect before Attack:
     - Blacklist, Whitelist
- Detect at the moment of Attack:
     - URL-Based, Content-Based, Rule-Based, Visual/Textual Similarities


## ProposeL System
- Our system uses Machine Learning algrorithms to classify Phishing and Legitimate websites with qualified performance. 
- URL-based technuiqes were analyzed. Followings are URL-based techniques:
  - Using long URL to hide doubtful part
  - Using tiny URL to hide a long URL
  - Having @ symbol in the URL
  - Adding known prefix or suffix to domain name
  - Using an IP adress in the URL
- WEKA tool is prefered to apply ML algoritmhs.


![image](https://user-images.githubusercontent.com/97549619/153664639-af340d27-39c9-43f1-bffe-1dd13f116dd5.png)

## Dataset

- Totally 126,077 website URLs.
- CatchPhish Dataset.*
   - Phishing websites from PhishTank
   - Legitimate websites from Common-crowl and Alexa	

## Data Preprocessing
Data preprocessing is a step to get qualified data. These steps are as follows:
- Data collecting
- Editing the format
- Importing libraries 
- Importing dataset to jupyter
- Missing value check
- Extract needed features
- Normalization
- Apply cross validation

## Features

- Moreover, after data preprocessing phase, we eliminated some missing, insufficient samples. Finally, we had 122,055 URLs.

- Total 15 features were used.

![image](https://user-images.githubusercontent.com/97549619/153666488-5edc50ae-44f1-4a66-ad50-7bd0738fe2a2.png)
## Machine Learning Algorithms

- **Random Forest :** Random forest is a popular algorithm as it can be used for both classification and regression problems. It works with tagged data which is called supervised learning. It classifies many decision trees and uses them to get better results.
-  **Decision Tree:** Tree-based learning algorithm is one of the most used algorithms for data mining classification. The algorithm, which has a tree-like model, makes some decisions to reach the desired results.
- **Naive Bayes** is based on Bayes’ theorem, a series of calculations based on probability princibles.
- **Logistic Regression** is the categorization problem of dependent variables used in the linear classification problem. 

## Results

- Confusion matrix is generated for each ML algorithm.
- According to these values, «Precision, Recall, F-1 Score» scores were calculated.

![image](https://user-images.githubusercontent.com/97549619/153666712-bbda80e3-8e23-419f-ad4c-5d2a708c98b2.png)

- **Precision** is the proportion of correct positive predictions.
- **Recall** is the proportion of correctly identified positive samples.
- **F1 score** is the harmonic mean of precision and recall values.

![image](https://user-images.githubusercontent.com/97549619/153666425-5db81760-49ad-42c9-95f9-0f59ff93697e.png)

## Conclusion
- Phishing is one of the most common cyber threats and it still cause huge financial losses. There are variable approaches to detect these attacks such as Content-based, Rule-based etc. and we prefered URL-based Approach.

- We used four different ML Algorithms and observed that Random Forest Classifier yields the highest results among the algorithms and Naive Bayes is the fastest one.

- URL-based techniques are quite efficient to classify Phishing and Legitimate websites.

- We observed that imbalance Dataset made difficult to get the right results.

## IEEE

We published this project at IEEE.This link is below.<br/>
**IEEE link:** [IEEE](https://ieeexplore.ieee.org/document/9358642)











