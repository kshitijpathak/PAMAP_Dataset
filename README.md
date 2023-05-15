# PAMAP Dataset
## 1. Introduction
PAMAP2 data set is a collection of 18 different physical activities; like walking, cycling, playing soccer among others performed by 9 subjects. Each of these subjects were wearing 3 inertial measurement units (IMUs) along with a heart rate monitor. The data for each subject is stored separately in text files. Each row represents an enrty and in total there are 54 columns. However, orientation columns are not valid in this collection so we will drop it in the data cleaning step. The goal of the analysis is to extract some actionable insights from the data which can help in further development of some software/harware to measure the amount and type of physical activity performed by an indivisual. The rest of the report is structured in the following fashion:

Data Preparation: reading and collating data from all text files
Data Cleaning: performing sanity checks and treating erroneous data
Exploratory Data Analysis: analysing data for any underlying trens and relationships between variables
Hypothesis Testing: conducting statistical tests to confirm the observed relationships
Model Development: developing a suitable model which builds upon the previous analyses
