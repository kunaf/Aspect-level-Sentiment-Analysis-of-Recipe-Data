# Aspect-level-Sentiment-Analysis-of-Recipe-Reviews-Data

This repository contains supporting documents for the dissertation of the project titled: “Enhancing Aspect-Level Sentiment Analysis in Recipe Reviews using a Pre-trained Transformer Model.” This folder contains supporting documents for this project. Among the supporting documents are the two source code documents.
Source Codes: 
1.	Data Annotation: This document contains source code in the python programming language, for the data annotation process of the Reviews dataset using pyABSA. It is a jupyter notebook named: recipe-review-annotation-with-pyabsa.ipynb. It was developed on Kaggle and can run on Kaggle or Google Colab. To successfully run the annotation, it requires sufficient GPU and memory capacity. 
2.	Aspect-Level Sentiment Analysis: This document contains source code in the python programming language, for the aspect-level sentiment analysis process. It is a jupyter notebook named: Aspect-level sentiment analysis with LSTM on DistilBERT.ipynb. It developed on google colab. The code can run on Google Colab. It requires TPU to run efficiently.
   
Data Sets:
To access the datasets used in this study the following will guide you:
1.	Annotated Dataset: This is a .json file containing labeled reviews. It is named: Aspect Term Extraction and Polarity Classification.FAST_LCF_ATEPC.result.json. This file is used in the Aspect-Level Sentiment Analysis source code. It is available on a public access google drive file. The source code contains a code snippet that allows any user of the source code to download this dataset into their current directory and work from there. To access this data set file, the use must authenticate themselves into their google drive account. 

2.	Recipe Review File: An excel file containing the recipe review column used in this study prior to annotation as well as other features. It is named: reviews.csv. If the annotation process is run in Kaggle, this file is optional. However, if the annotation process is run in colab, the reviews file can be gotten following the same procedure as with the annotated dataset file. The source code, Jupyter notebook contains further instructions and a code snippet to run the whole process
