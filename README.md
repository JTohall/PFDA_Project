# PFDA_Project
Programming for Data Analysis Assessment 

---

### Problem Statement
<br/>
This project will investigate the Wisconsin Breast Cancer dataset. The following list presents the requirements of the project:
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
Investigation of Dataset Extension<br/>
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
[1] https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Original%29<br/>
[2]https://www.researchgate.net/publication/311950799_Analysis_of_the_Wisconsin_Breast_Cancer_Dataset_and_Machine_Learning_for_Breast_Cancer_Detection<br/>
[3] https://data.world/health/breast-cancer-wisconsin/workspace/file?filename=DatasetDescription.txt<br/>
[4] https://pubmed.ncbi.nlm.nih.gov/15460731/<br/>
[5] https://1library.net/document/download/q5wodwwq?page=1<br/>
[6] https://node1.123dok.com/dt01pdf/123dok_us/000/791/791788.pdf.pdf?X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=7PKKQ3DUV8RG19BL%2F20230109%2F%2Fs3%2Faws4_request&X-Amz-Date=20230109T203933Z&X-Amz-SignedHeaders=host&X-Amz-Expires=600&X-Amz-Signature=05680f6a49547c0f47ffeb4662633159d5433730fc1692feb29475f0a6318434<br/>
[7] https://www.youtube.com/watch?v=2ncx2q5GHbQ<br/>
[8] http://dx.doi.org/10.4236/oalib.1100660<br/>
[9] https://www.researchgate.net/publication/355027167_Machine_Learning_Classifiers_on_Breast_Cancer_Recurrences<br/>
[10] https://www.who.int/news-room/fact-sheets/detail/breast-cancer<br/>
[11] https://www.cancer.org/healthy/cancer-facts/cancer-facts-for-women.html<br/>
[12] https://machinemantra.in/breast-cancer-wisconsin-dataset/<br/>
[13] https://www.ijert.org/research/study-and-analysis-of-breast-cancer-data-IJERTCONV5IS21015.pdf<br/>
[14] https://www.geeksforgeeks.org/ml-kaggle-breast-cancer-wisconsin-diagnosis-using-knn/?ref=gcse<br/>
[15] https://deepai.org/machine-learning-glossary-and-terms/classifier#:~:text=A%20classifier%20is%20any%20algorithm%20that%20sorts%20data,pattern%20recognition%20in%20many%20forms%20of%20machine%20learning.<br/>
[16] https://www.javatpoint.com/perceptron-in-machine-learning<br/>
[17] https://www.javatpoint.com/machine-learning-decision-tree-classification-algorithm<br/>
[18] https://towardsdatascience.com/logistic-regression-classifier-8583e0c3cf9<br/>
[19] https://www.indeed.com/career-advice/career-development/classifiers-in-machine-learning#:~:text=5%20types%20of%20classifiers%20in%20machine%20learning%201,vector%20machine%20...%205%205.%20K-nearest%20neighbor%20<br/>
[20] https://www.analyticssteps.com/blogs/types-classifiers-machine-learning<br/>
[21] https://www.kaggle.com/code/rcfreitas/python-ml-breast-cancer-diagnostic-data-set<br/>
[22] https://medium.com/data-science-101/exploring-breast-cancer-data-set-b1053ea71781<br/>
[23] https://machinemantra.in/breast-cancer-wisconsin-dataset/<br/>
[24] https://www.engineeringbigdata.com/breast-cancer-prediction-using-random-forest-algorithm-in-python/<br/>
