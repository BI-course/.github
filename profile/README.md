# GitHub Organization for the BBT4106 and BBT4206 Business Intelligence I and II Courses

A GitHub organization used to facilitate and manage collaboration amongst students taking the BBT4106 and BBT4206 Business Intelligence I and II courses respectively.

| **Key**                                                               | Value                                                                                                                                                                              |
|---------------|---------------------------------------------------------|
| **Course Code**                                                       | BBT4106 and BBT4206                                                                                                                                                                            |
| **Course Name**                                                       | Business Intelligence I and II respectively                                                                                                                                                           |
| **URL**                                                               | <https://elearning.strathmore.edu/course/view.php?id=6462> and <https://elearning.strathmore.edu/course/view.php?id=6599> respectively                                                                                                                         |
| **Current Semester Duration**                                                 | _Not currently on offer_                                                                                                                       |
| **Lecturer**                                                          | Allan Omondi                                                                                                                                                                       |
| **Contact**                                                           | aomondi@strathmore.edu                                                                                                                                                      |

## Past Semesters

* BBT4206: 21<sup>st</sup> August 2023 to 28<sup>th</sup> November 2023
* BBT4106: 12<sup>th</sup> April 2023 to 19<sup>th</sup> July 2023

<hr>

* BBT4206 (Exempt): 12<sup>th</sup> April 2023 to 19<sup>th</sup> July 2023
* BBT4106 (Exempt): 28<sup>th</sup> November 2022 to 30<sup>th</sup> March 2023

<hr>

* BBT4206 (Evening): 23<sup>rd</sup> January 2023 to 13<sup>th</sup> April 2023
* BBT4106 (Evening): 20<sup>th</sup> September 2022 to 20<sup>th</sup> December 2022

## Labs
Part of the course is based on the following 9 steps of **Knowledge Discovery in Databases (KDD)**:

## Step 1: Problem Definition and Goal Setting

This involves an understanding of the problem, the requirements of the end-user for the solution to the problem, and the environment in which the KDD process will occur.

-   *BI Project: Section 1, 3, and 14*

## Step 2: Data Selection

This involves discovering what data is accessible, selecting the significant data that is accessible, and then integrating all this data into one set (a dataset). It is extremely important to ensure that the data is collected ethically (informed consent), and that the data is not biased (the sample should represent the population). The entire KDD process may be unsuccessful if there are significant attributes/features missing in the dataset. This can be performed by the data engineer.

-   *Concept: Data Engineering*

## Step 3: Data Cleansing and Pre-Processing

This involves describing data to better understand it. Through this understanding, outliers and noise can be removed, and missing data can be estimated (data imputation can be performed). For example, this stage can involve the correction of invalid postal codes, or the elimination of records with incorrect phone prefixes, or the removal of currency symbols, e.g., '\$', ¥, '€', etc. This can be performed by the data engineer.

-   *Lab1-LoadingDatasets.R*

-   *Lab2a-ExploratoryDataAnalysisForQuantitativeData.R*

-   *Lab2b-ExploratoryDataAnalysisForQualitativeData.R*

-   *Lab2c-SentimentAnalysis.R*

-   *Lab3-DataImputation.R*

## Step 4: Data Transformation

This involves finding useful features that represent the data according to the goal of addressing the problem defined. In doing so, the structure of the data and the prediction problem is exposed to data mining algorithms. Finding useful attributes/features can also be done through dimensionality reduction (identifying the most significant and uncorrelated attributes). This can be performed by a data analyst.

-   *Lab4-ExposingTheStructureOfDataUsingDataTransforms.R*

## Step 5: Selection of the Data Mining Task

This involves deciding whether to use data mining to either predict classifications, regressions, associations, or clusters. The decision is based on the goal of the KDD process. Step 5-7 can be performed by a Machine Learning engineer and/or a data analyst.

-   *BI Project Section 3*

## Step 6: Selection of the Data Mining Algorithm

Evaluate several standard algorithms on the data and shortlist the top performing algorithms to investigate further

-   *Lab5-ControllingComputationalNuancesofAlgorithms.R*

-   *Lab6-EvaluationMetrics.R*

-   *Lab7-ModelSelection.R*

-   *Lab8-ModelPerformanceComparison.R*

## Step 7: Utilization of the Data Mining Algorithm

The chosen algorithm is then used to train the model. Knowledge is represented in the form of patterns and rules in a model. Algorithm tuning and ensemble methods are used at this point to get the most out of well performing algorithms.

-   *Lab9-AlgorithmParameterTuning.R*

-   *Lab10-EnsembleMethods.R*

-   *Lab11-FinalizingtheModel.R*

## Step 8: Interpretation and Evaluation

The knowledge represented in the form of patterns and rules is then **validated by domain experts** based on the problem defined in [Step 1](#step-1-problem-definition-and-goal-setting) and the goal of the KDD process. The domain expert, in this case, **DOES NOT** refer to the IT practitioner who trained the model. The domain experts can include medical doctors, psychologists, economists, meteorologists, political scientists, pharmacists, etc. depending on the area under study. If the knowledge discovered is not valid, then the KDD process is repeated from [Step 2](#step-2-data-selection) by reconsidering the attributes/features.

## Step 9: Consolidation

This involves operationalizing the knowledge discovered by integrating it into an Information System (e.g., a data visualization dashboard). This step is exposed to the challenge of losing the "laboratory environment" in which the model was trained. This laboratory environment handled pre-processed, static data whereas the actual environment is based on dynamic data that can contain outliers and noise. Despite this significant challenge, the accomplishment of this step determines the effectiveness of the entire KDD process.

-   *BI Project Section 15 and Section 16*

-   *Lab12-Plumber-API.R*

-   *Lab13-Run-Plumber-API.R*

-   *Lab14-Consume-Plumber-API-Output.R*

-   *Lab15-Consume-Plumber-API-Output.php*
