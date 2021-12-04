# ML FAQ Project

## Overview
This is a project to develop an interface to answer questions about New Mexico State University's (NMSU) Computer Science Graduate program.

## File Descriptions
* Cleaned_Questions.csv - This is a comment separated values file containing two columns of data. The first column consists of candid NMSU FAQs from the sites and the second column consists of the questions' respective answers. The data is from NMSU's Computer Science Department website ([here](https://computerscience.nmsu.edu/grad-students/prospective-graduates.html#FAQs) and [here](https://computerscience.nmsu.edu/grad-students/graduate-student-faq.html)).


* ML_Mini_Project.pdf - This is a project report consisting of a breakdown of the models made and their performance.

* ML_Mini_Project_Code.ipynb - This is the code for the project that contains the models tested as well as the framework for a prototype.

* Project_mini.docx - These are the project requirements.

* QandA.xlsx - These are the unrefined questions and answers from the same source as Cleaned_Questions.csv.

* prototype.py - This is a python file that downloads all necessary libraries and runs an input driven simulation for a student question interface.

## Execution
* ML_Mini_Project_Code.ipynb - To execute the project code, just run it in any python notebook executor (Jupyter, Google Colab), and all of the required libraries should automatically download. Just make sure that the 'Cleaned_Questions.csv' is in the sasme directory.

* prototype.py - To execute the prototype, just run with python3 in the command line. All of the required libraries should be downloaded, and the prototype will start with its initial prompt. Just make sure to have 'Cleaned_Questions.csv' in the sasme directory.