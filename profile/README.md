# GitHub Organization for the BBT4106 and BBT4206 Business Intelligence I and II Courses

A GitHub organization used to facilitate and manage collaboration amongst students taking the BBT4106 and BBT4206 Business Intelligence I and II courses respectively.

| **Key**                                                               | Value                                                                                                                                                                              |
|---------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------|
| **Course Code**                                                       | BBT4106 and BBT4206                                                                                                                                                                            |
| **Course Name**                                                       | Business Intelligence I and Business Intelligence II respectively                                                                                                                                                           |
| **Most Recent Active Semester**                                                 | 2026 April-July                                                                                                                                                                                        |
| **Lecturer**                                                          | Allan Omondi                                                                                                                                                                       |
| **Contact**                                                           | aomondi@strathmore.edu                                                                                                                                                      |

## Purpose of Business Intelligence I

The purpose of this course is to build your foundational knowledge and technical skills in business intelligence, data engineering, data analytics, data visualization, and classical machine learning techniques, enabling you to derive accurate and actionable business insights.

## Purpose of Business Intelligence II

The purpose of this course is to advance your ability to apply classical machine learning techniques—clustering, recommender systems, model deployment through REST APIs, time-series forecasting, and natural language processing—to generate insights and solutions that address real-world business challenges.

## Labs

Various labs in the course contribute towards learning the following 9 steps of **Knowledge Discovery in Databases (KDD)**:

## Step 1: Problem Definition and Goal Setting

This involves an understanding of the problem, the requirements of the end-user for the solution to the problem, and the environment in which the KDD process will occur.

## Step 2: Data Selection

This involves discovering what data is accessible, selecting the significant data that is accessible, and then integrating all this data into one set (a dataset). It is important to ensure that the data is collected ethically (informed consent), and that the data is not biased (the sample should represent the population). The entire KDD process may be unsuccessful if there are significant attributes/features missing in the dataset. This can be performed by the data engineer.

## Step 3: Data Cleansing and Pre-Processing

This involves describing data to better understand it. Through this understanding, outliers and noise can be removed, and missing data can be estimated (data imputation can be performed). Example: this stage can involve the correction of invalid postal codes, or the elimination of records with incorrect phone prefixes, or the removal of currency symbols, e.g., ‘$’, ¥, ‘€’, etc. This can be performed by the data engineer.

## Step 4: Data Transformation

This involves exposing the structure of the data to the algorithm. Data transformation techniques include: Scaling (dividing each value by the standard deviation), Centering (subtracting the mean from each value), Standardization (ensuring that each numeric attribute has a mean value of 0 and a standard deviation of 1—this is done by combining the scale data transform and the center data transform, Normalization (ensuring the numerical data are between [0, 1] (inclusive), Box-Cox and Yeo-Johnson transforms (reduce the skewness by shifting the distribution of an attribute and making the attribute have a more Gaussian-like distribution). 

Data Transformation techniques also including encoding (transforming categorical data into a numerical format). Types of encoding include: one-hot encoding (creates a binary column for every category), label-encoding and ordinal encoding (assign each category a unique integer)

Finding useful attributes/features can also be done through dimensionality reduction (identifying the most significant and uncorrelated attributes). This can be performed by a data analyst.

## Step 5: Selection of the Data Mining Task

This involves deciding whether to use data mining to either describe associations and clusters or to predict a class or a numeric value. This can (and should) be extended to an optimization task that involves prescribing what should be done in the present based on the desired future state. Machine Learning engineers and data analysts play a critical role in Step 5-7 of the KDD process.

## Step 6: Selection of the Data Mining Algorithm

Evaluate several (not one) standard algorithms on the data and shortlist the top performing algorithms to investigate further.

## Step 7: Utilization of the Data Mining Algorithm

The chosen algorithm is then used to train the model. Hyperparameter tuning and ensemble methods can be used at this point to get the most out of well performing algorithms.

## Step 8: Interpretation and Evaluation

The knowledge represented in the form of patterns and rules is then validated by domain experts based on the problem defined in Step 1 and the aim of the research/project. The domain expert, in this case, DOES NOT refer to the IT practitioner (data analyst, data miner, ML engineer, data scientist, etc.) who trained the model. The domain experts can include business administrators, medical doctors, psychologists, economists, meteorologists, political scientists, pharmacists, etc. depending on the area under study. If the knowledge discovered is not valid, then the KDD process is repeated from Step 2 by reconsidering the attributes/features. A simple user interface (in the frontend) can be used by the domain experts to access the model (in the backend) and validate it (provide feedback according to their expertise). Possible options for such platforms include [Hugging Face Spaces](https://huggingface.co/spaces), [Render](https://dashboard.render.com/), and [Streamlit Apps](https://share.streamlit.io/), etc.

## Step 9: Consolidation

This involves operationalizing the knowledge discovered by integrating it into an Information System. This step is exposed to the challenge of losing the “laboratory environment” in which the model was designed. This laboratory environment handled pre-processed static data whereas the actual environment is based on dynamic data that can contain outliers and noise. Despite this significant challenge, the accomplishment of this step determines the effectiveness of the entire KDD process.
