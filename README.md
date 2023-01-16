
# Programming for Data Analysis

<br/>

## Project II
# An Analysis of the Wisconsin Breast Cancer Dataset

<br/>

Author: Jamie Tohall<br/>
Student Number: G00411380<br/>
Lecturer: Brian McGinley<br/>

<br/>

---

<br/>

### Problem Statement

<br/>
This project will investigate the Wisconsin Breast Cancer dataset. The following list presents the requirements of the project:<br/>

<br/>

- Undertake an analysis/review of the dataset and present an overview and background.<br/>
- Provide a literature review on classifiers which have been applied to the dataset and compare their performance<br/>
- Present a statistical analysis of the dataset<br/>
- Using a range of machine learning algorithms, train a set of classifiers on the dataset (using SKLearn etc.) and present classification performance results. Detail your rationale for the parameter selections you made while training the classifiers.<br/>
- Compare, contrast and critique your results with reference to the literature<br/>
- Discuss and investigate how the dataset could be extended – using data synthesis of new tumour datapoints<br/>
- Document your work in a Jupyter notebook.<br/>
- As a suggestion, you could use Pandas, Seaborn, SKLearn, etc. to perform your analysis.<br/>
- Please use GitHub to demonstrate research, progress and consistency.<br/>

<br/>

---

<br/>

### Contents

<br/>

Problem Statement<br/>
Introduction<br/>
Dataset Description<br/>
Different types of Classifiers<br/>
Literature Review<br/>
Importing Relevant Modules<br/>
Reading in the Dataset<br/>
Preprocessing of the Dataset<br/>
Cleaning and Preparing the Dataset<br/>
Statistical Analysis<br/>
Training a Set of Classifiers<br/>
Review of Results<br/>
References<br/>

<br/>

---

## Introduction

<br/>

Breast cancer occurs in every single country of the world in women at any postpubescent age but with increasing rates in later life.
The World Health Organisation states that in 2020 there were 2.3 million women diagnosed with breast cancer, and 685,000 deaths globally, making breast cancer the most common cancer in women. One in eight women are diagnosed with breast cancer in a lifetime, fortunately, this rate is decreasing with awareness but still many women are not aware of the early signs or symptoms.

<br/>

Breast cancer arises in the lining cells of the ducts or lobules in the glandular tissue of the breast. Initially, the cancerous growth is confined to the duct or lobule, where it generally causes no symptoms and has minimal potential for spread. However over time and without any treatment, these stage 1 cancers may progress and invade the surrounding breast tissue, developing into an invastive breast cancer which will then spread to the nearby lymph nodes or to other organs in the body, this is also known as distant metastasis. If a woman dies from breast cancer, it is because of widespread metastasis.

<br/>
Breast cancer treatment can be highly effective, especially when the disease is identified early. Treatment of breast cancer often consists of a combination of surgical removal, radiation therapy and medication (hormonal therapy, chemotherapy and/or targeted biological therapy) to treat the microscopic cancer that has spread from the breast tumor through the blood. Such treatment, which can prevent cancer growth and spread, thereby saves lives.

<br/>

For this project, I will analyse the Wisconsin breast cancer dataset. The dataset was developed in 1995 by researchers at the University of Wisconsin, and includes the measurements from digitized images of fine-needle aspirate of a breast mass. A fine-needle aspirate is a type of biopsy performed using a small needle to obtain samples of tissue and fluid from solid or cystic breast lesions. It is one of the many different modalities for diagnosing breast masses.

<br/>
The breast cancer dataset includes 569 examples of cancer biopsies, each with 32 features. One feature is an identification number, another is the cancer diagnosis and 30 are numeric-valued laboratory measurements. The diagnosis is coded as "M" to indicate malignant or "B" to indicate benign.

<br/>
The other 30 numeric measurements comprise the mean, standard error and worst (i.e. largest) value for 10 different characteristics of the digitized cell nuclei, which are as follows:-<br/>

<br/>

Radius<br/>
Texture<br/>
Perimeter<br/>
Area<br/>
Smoothness<br/>
Compactness<br/>
Concavity<br/>
Concave Points<br/>
Symmetry<br/>
Fractal dimension<br/>

<br/>

---

<br/>

## References

<br/>
[1] Ahmed, T. Imtiaz, M. & Karmakar, A. (2020) *Analysis of Wisconsin Breast Cancer Original Dataset using Data Mining and Machine Learning Algorithms for Breast Cancer Prediction.* Available at: https://www.researchgate.net/publication/343260505_Analysis_of_Wisconsin_Breast_Cancer_original_dataset_using_data_mining_and_machine_learning_algorithms_for_breast_cancer_prediction (Accessed: 6 Jan 2023)
<br/>

[2] American Cancer Society (2021) *Cancer facts for Women.* Available at: https://www.cancer.org/healthy/cancer-facts/cancer-facts-for-women.html (Accessed: 3 Jan 2023)
<br/>

[3] Borges, L. (2015) *Analysis of the Wisconsin Breast Cancer Dataset and Machine Learning for Breast Cancer Detection.* Available at: https://www.researchgate.net/publication/311950799_Analysis_of_the_Wisconsin_Breast_Cancer_Dataset_and_Machine_Learning_for_Breast_Cancer_Detection (Accessed: 29 dec 2022)
<br/>

[4] Camargo De Freitas, R. (2018) *Python ML - breast cancer diagnostic data set.* Available at: https://www.kaggle.com/code/rcfreitas/python-ml-breast-cancer-diagnostic-data-set (Accessed: 6 Jan 2023)
<br/>

[5] DeepAI (2021) *What is a Classifier in Machine Learning?* Available at: https://deepai.org/machine-learning-glossary-and-terms/classifier#:~:text=A%20classifier%20is%20any%20algorithm%20that%20sorts%20data,pattern%20recognition%20in%20many%20forms%20of%20machine%20learning. (Accessed: 4 Jan 2023)
<br/>

[6] Dutta, B. (2022) *6 Types of Classifiers in Machine Learning.* Available at: https://www.analyticssteps.com/blogs/types-classifiers-machine-learning (Accessed: 3 Jan 2022)
<br/>

[7] Engineeringbigdata (2019) *Breast Cancer Dataset Analysis, Visualization and Machine Learning in Python.* Available at: https://www.engineeringbigdata.com/breast-cancer-dataset-analysis-visualization-and-machine-learning-in-python/ (Accessed 15 Jan 2023)
<br/>

[8] Engineeringbigdata (2019) *Breast Cancer Prediction using Random Forest Algorithm in Python.* Available at: https://www.engineeringbigdata.com/breast-cancer-prediction-using-random-forest-algorithm-in-python/ (Accessed: 9 Jan 2023)<br/>

[9] Gupta, M. (2020) *ML|Kaggle Breast Cancer Wisconsin Diagnosis using KNN and Cross Validation.* Available at: https://www.geeksforgeeks.org/ml-kaggle-breast-cancer-wisconsin-diagnosis-using-knn/?ref=gcse (Accessed: 5 Jan 2023)
<br/>

[10] Indeed (2022) *Machine Learning Classifiers: Definition and 5 Types.* Available at: https://www.indeed.com/career-advice/career-development/classifiers-in-machine-learning (Accessed: 30 Dec 2022)
<br/>

[11] Jain, A. (2018) *Exploring Breast Cancer Data set.* Availalbe at: https://medium.com/data-science-101/exploring-breast-cancer-data-set-b1053ea71781 (Accessed: 28 Dec 2022)
<br/>

[12] Java T Point (2020) *Decision Tree Classification Algorithm.* Available at: https://www.javatpoint.com/machine-learning-decision-tree-classification-algorithm (Accessed: 6 Jan 2023)
<br/>

[13] Java T Point (2020) *Perceptron in Machine Learning.* Available at: https://www.javatpoint.com/perceptron-in-machine-learning (Accessed: 6 Jan 2023)
<br/>

[14] Kagolovsky, Y. Moehr, J. & Pantazi, S. (2002) *Cluster analysis of Wisconsin Breast Cancer dataset using self-organizing maps.* Available at: https://pubmed.ncbi.nlm.nih.gov/15460731/ (Accessed 2 Jan 2023) 
<br/>

[15] Machine Mantra (2020) *Breast Canser Wisconsin Dataset: Machine Learning Project in Python*. Available at: https://www.youtube.com/watch?v=2ncx2q5GHbQ (Accessed: 30 Dec 2022)
<br/>

[16] Machine Mantra (2020) *Breast Cancer Wisconsin Project: Python Tutorial.* Available at: https://machinemantra.in/breast-cancer-wisconsin-dataset/ (Accessed: 5 Jan 2023)
<br/>

[17] Manoli, S. & Padma, S.K. (2017) *Study and Analysis of Breast Cancer Data.* Available at: https://www.ijert.org/research/study-and-analysis-of-breast-cancer-data-IJERTCONV5IS21015.pdf (Accessed: 4 Jan 2023)
<br/>

[18] Magboo, S & Magboo, V. (2021) *Machine Learning Classifiers on Breast Cancer Recurrences.* Available at: https://www.sciencedirect.com/science/article/pii/S1877050921017816 (Accessed: 23 Dec 2022)
<br/>

[19] Paithankar, M. (2020) *Breast Cancer Classification Using Python: A guide to EDA and classification.* Available at: https://medium.com/swlh/breast-cancer-classification-using-python-e83719e5f97d (Accessed: 15 Jan 2023)
<br/>

[20] Subasi, C. (2019) *Logistic Regression Classifier.* Available at: https://towardsdatascience.com/logistic-regression-classifier-8583e0c3cf9 (Accessed: 7 Jan 2023)
<br/>

[21] Vig, L. (2014) *Comparative Analysis of Different Classifiers for the Wisconsin Breast Cancer Dataset.* Available at: https://www.academia.edu/73175278/Comparative_Analysis_of_Different_Classifiers_for_the_Wisconsin_Breast_Cancer_Dataset (Accessed: 2 Jan 2023)
<br/>

[22] Wolberg, W. (1995) *Breast Cancer Wisconsin (Original) Data Set.* Available at: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Original%29 (Accessed: 20 Dec 2022)
<br/>

[23] Wolberg, W. (1995) *Breast Cancer Dataset Description.* Available at:
https://data.world/health/breast-cancer-wisconsin/workspace/file?filename=DatasetDescription.txt (Accessed: 20 Dec 2022) <br/>

[24] World Health Organization (2021) *Breast Cancer.* Available at: https://www.who.int/news-room/fact-sheets/detail/breast-cancer (Accessed: 3 Jan 2023)
<br/>

[25] Yahyaoui, H (2022) *Naive bayes from scratch/Breast cancer.* Available at: https://www.kaggle.com/code/helayahyaoui/naive-bayes-from-scratch-breast-cancer (Accessed: 15 Jan 2023)
