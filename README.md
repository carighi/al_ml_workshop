# Intro to Data Science Course: AI/ML
  - [Introduction](#introduction)
  - [Source](#source)
  - [Content](#content)

## Introduction
Research is being revolutionized by methods from the field of Artificial Intelligence and Machine Learning (AI/ML). AI is the simulation of human intelligence processes (such as problem-solving, learning, and planning) by machines, while ML, a type of artificial intelligence, gives computers the ability to learn without explicitly being programmed. They have been applied in many areas including drug discovery, protein folding, and identification of variants from genetic data.

This part of the course will provide you with

- a conceptual understanding of various AI/ML approaches,
- examples of practical applications of AI/ML in computational biology and chemistry,
- hands-on exercises with emphasis on the importance of data preparation and readiness for AI/ML.

Through the lectures accessible via CANVAS modules, you will be exposed to the basic concepts behind AI/ML approaches to better understand the practical applications of these data science tools, including what types of data can be used for a specific approach, and what types of outcomes can be expected. The illustrative practical applications will help you understand how these tools can be used in your research project. You will also learn about the importance of preparing the data according to the FAIR principles, namely, [Findability, Accessibility, Interoperability, and Reusability](https://pubmed.ncbi.nlm.nih.gov/26978244/). This will be addressed by providing you with first-hand experience on the issues arising when data that is not well-prepared, and covering various data formats, processing and wrangling techniques to get the data into a form where it can be utilized by Machine Learning algorithms. You will learn different visualization techniques to better understand the data at hand.

## Source

The content in this course is based on Practical AI/ML for Computational Biology and Chemistry Workshop (June 13-17, 2022, UD)
https://github.com/udel-cbcb/al_ml_workshop

## Content

<b>Module 16 Intro to popular Python Libraries/Packages for ML</b>

- Intro to tools and libraries
  - [Introduction to Google Colab](https://colab.research.google.com/github/carighi/al_ml_workshop/blob/main/Module_1/Live_Demos/Day_1_Live_Demo_1_Introduction_to_Google_Colab.ipynb)
  - [Introduction to NumPy](https://github.com/carighi/al_ml_workshop/blob/main/NumPy_exercises.ipynb)
  - [Introduction to Pandas](https://github.com/carighi/al_ml_workshop/blob/main/Introduction_to_Pandas_tutorial.ipynb)
  - [Predict Gene Family using DNA Sequence](https://colab.research.google.com/github/carighi/al_ml_workshop/blob/main/Module_1//Live_Demos/Day_1_Live_Demo_4_Predict_Gene_Family_Using_DNA_Sequence.ipynb)
- Exercises
  - [NumPy Exercise](https://colab.research.google.com/github/carighi/al_ml_workshop/blob/main/Module_1/Exercises/Day_1_Exercise_NumPy.ipynb) ([Solution](https://colab.research.google.com/github/carighi/al_ml_workshop/blob/main/Module_1/Exercises/Day_1_Exercise_NumPy_Solution.ipynb))
  - [Pandas Exercise](https://colab.research.google.com/github/carighi/al_ml_workshop/blob/main/Module_1/Exercises/Day_1_Exercise_Pandas.ipynb) ([Solution](https://colab.research.google.com/github/carighi/al_ml_workshop/blob/main/Module_1/Exercises/Day_1_Exercise_Pandas_Solution.ipynb))

<b>Module 18 Data Preparation 1</b>
- Demo
  - [Basic Data Cleaning](https://github.com/carighi/al_ml_workshop/blob/main/Basic_Data_Cleaning.ipynb)
  - [Marking and Removal of Missing Data](https://colab.research.google.com/github/carighi/al_ml_workshop/blob/main/Day_2/Live_Demos/Day_2_Live_Demo_2_Mark_and_Remove_Missing_Data.ipynb)
  - [Outlier Identification and Removal](https://colab.research.google.com/github/carighi/al_ml_workshop/blob/main/Day_2/Live_Demos/Day_2_Live_Demo_3_Outlier_Identification_and_Removal.ipynb)
  - [Missing Data Imputation](https://colab.research.google.com/github/carighi/al_ml_workshop/blob/main/Day_2/Live_Demos/Day_2_Live_Demo_4_Missing_Data_Imputation.ipynb)
- Exercises
  - [Data Wrangling Exericse](https://colab.research.google.com/github/carighi/al_ml_workshop/blob/main/Day_2/Exercises/Day_2_Exercise_Data_Wrangling.ipynb) ([Solution](https://colab.research.google.com/github/carighi/al_ml_workshop/blob/main/Day_2/Exercises/Day_2_Exercise_Data_Wrangling_Solution.ipynb))

<b>Module 19 Feature selection for ML</b>
- Demo
  - Feature Engineering
    - [Encode Categorical Data](https://colab.research.google.com/github/carighi/al_ml_workshop/blob/main/Day_3/Live_Demos/Day_3_Live_Demo_1_Feature_Engineering_Encode_Categorical_Data.ipynb)
    - [Change Numerical Data Distribution](https://colab.research.google.com/github/carighi/al_ml_workshop/blob/main/Day_3/Live_Demos/Day_3_Live_Demo_2_Feature_Engineering_Change_Numerical_Data_Distributions.ipynb)
    - [Derive New Input Variables](https://colab.research.google.com/github/carighi/al_ml_workshop/blob/main/Day_3/Live_Demos/Day_3_Live_Demo_3_Feature_Engineering_Derive_New_Input_Variables.ipynb)
  - Feature Scaling
    - [Numerical Data](https://colab.research.google.com/github/carighi/al_ml_workshop/blob/main/Day_3/Live_Demos/Day_3_LIve_Demo_4_Feature_Scaling_Numerical_Data.ipynb)
    - [Data With Outliers](https://colab.research.google.com/github/carighi/al_ml_workshop/blob/main/Day_3/Live_Demos/Day_3_Live_Demo_5_Feature_Scaling_Data_with_Outliers.ipynb)
  - Feature Selection
    - [Numerical Input Features](https://colab.research.google.com/github/carighi/al_ml_workshop/blob/main/Day_3/Live_Demos/Day_3_Live_Demo_6_Feature_Selection_Categorical_Input_Features.ipynb)
    - [Categorical Input Features](https://colab.research.google.com/github/carighi/al_ml_workshop/blob/main/Day_3/Live_Demos/Day_3_LIve_Demo_7_Feature_Selection_Numerical_Input_Features.ipynb)
    - [Recursive Feature Elimination](https://colab.research.google.com/github/carighi/al_ml_workshop/blob/main/Day_3/Live_Demos/Day_3_Live_Demo_8_Feature_Selection_Recursive_Feature_Elimination.ipynb)
- Exercises
  - [Feature Engineering Exercise](https://colab.research.google.com/github/carighi/al_ml_workshop/blob/main/Day_3/Exercises/Day_3_Exercise_Feature_Engineering.ipynb) ([Solution](https://colab.research.google.com/github/carighi/al_ml_workshop/blob/main/Day_3/Exercises/Day_3_Exercise_Feature_Engineering_Solution.ipynb))
  - [Feature Scaling Exercise](https://colab.research.google.com/github/carighi/al_ml_workshop/blob/main/Day_3/Exercises/Day_3_Exercise_Feature_Scaling.ipynb) ([Solution](https://colab.research.google.com/github/carighi/al_ml_workshop/blob/main/Day_3/Exercises/Day_3_Exercise_Feature_Scaling_Solution.ipynb))
  - [Feature Selection Exercise](https://colab.research.google.com/github/carighi/al_ml_workshop/blob/main/Day_3/Exercises/Day_3_Exericse_Feature_Selection.ipynb) ([Solution](https://colab.research.google.com/github/carighi/al_ml_workshop/blob/main/Day_3/Exercises/Day_3_Exericse_Feature_Selection_Solution.ipynb))

<b>Module 21 Models: from their Selection to Training, Evaluation and Tuning</b>
- Demo
  - [Predict Drug Activity for Androgen Receptor](https://colab.research.google.com/github/carighi/al_ml_workshop/blob/main/Day_4/Live_Demos/Day_4_Live_Demo_1_Predict_Drug_Activity_for_Androgen_Receptor.ipynb)
  - [Model Building and Evaluation](https://colab.research.google.com/github/carighi/al_ml_workshop/blob/main/Day_4/Live_Demos/Day_4_Live_Demo_2_Model_Building_and_Evaluation.ipynb)
  - [Model Tuning, Interpretation, Deployment](https://colab.research.google.com/github/carighi/al_ml_workshop/blob/main/Day_4/Live_Demos/Day_4_Live_Demo_3_Model_Tunning_Interpretation_Deployment.ipynb)
- Exercises
  - [Exploratory Analysis of Wine Types and Quality Data](https://colab.research.google.com/github/carighi/al_ml_workshop/blob/main/Day_4/Exercises/Day_4_Exercise_1_Exploratory_Analysis_of_Wine_Types_and_Quality_Data.ipynb) ([Solution](https://colab.research.google.com/github/carighi/al_ml_workshop/blob/main/Day_4/Exercises/Day_4_Exercise_1_Exploratory_Analysis_of_Wine_Types_and_Quality_Data_Solution.ipynb))
  - [Predict Wine types using physicochemical features](https://colab.research.google.com/github/carighi/al_ml_workshop/blob/main/Day_4/Exercises/Day_4_Exercise_2_Predicting_Wine_Types.ipynb) ([Solution](https://colab.research.google.com/github/carighi/al_ml_workshop/blob/main/Day_4/Exercises/Day_4_Exercise_2_Predicting_Wine_Types_Solution.ipynb))
  - [Predict Wine quality using physicochemical features](https://colab.research.google.com/github/carighi/al_ml_workshop/blob/main/Day_4/Exercises/Day_4_Exercise_3_Predicting_Wine_Quality.ipynb) ([Solution](https://colab.research.google.com/github/carighi/al_ml_workshop/blob/main/Day_4/Exercises/Day_4_Exercise_3_Predicting_Wine_Quality_Solution.ipynb))

<b>Module 23 Deep Learning Applications</b>
- Demo
  - [Pfam protein sequence classification using Tensorflow and Keras](https://colab.research.google.com/github/carighi/al_ml_workshop/blob/main/Day_5/Live_Demos/Day_5_Live_Demo_1_Pfam_Protein_Sequence_Classification_with_Tensorflow_Keras.ipynb)
  - [Predicting molecule solubility using DeepChem](https://colab.research.google.com/github/carighi/al_ml_workshop/blob/main/Day_5/Live_Demos/Day_5_Live_Demo_2_Predicting_the_Solubility_of_Small_Molecules.ipynb)
- Exercises
  - [Predict Wine types using Deep Learning](https://colab.research.google.com/github/carighi/al_ml_workshop/blob/main/Day_5/Exercises/Day_5_Exercise_1_Predicting_Wine_Types_Deep_Learing.ipynb) ([Solution](Day_5/Exercises/Day_5_Exercise_1_Predicting_Wine_Types_Deep_Learing_Solution.ipynb))
  - [Protein 3D structure prediction using AlphaFold2](https://colab.research.google.com/github/deepmind/alphafold/blob/main/notebooks/AlphaFold.ipynb)

<b>Additional exercises</b>
- Exercises
  - [Modules 15 and 16](https://colab.research.google.com/github/carighi/al_ml_workshop/blob/main/Additional_exercises/Exercises_additional_1.ipynb) 
