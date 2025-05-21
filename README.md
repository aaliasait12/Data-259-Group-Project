# Data-259-Group-Project
Contributors: Aalia Sait, Ayesha Ramnani, George Lin 

# Face-Off: Human and AI Emotion Perception

Our project aims to investigate the following ethical question: <br>
To what extent do AI facial analysis models reflect or amplify race and gender based biases in emotion perception, and what are the potential ethical implications of their use in real-world contexts?

## Brief Overview of our Qualitative Methods: 

### 1. Literature Review 
a. Analyze key literature for background research and to motivate our research question
b. Understand the real-world ethical stakes of facial recognition technology. 

## Brief Overview of Quantitative Methods: 

### 1. Data Collection  
a. Use the FairFace Train dataset for our image collection.   <br>

### 2. Human Survey 
a. Use Qualtrics to build a survey to gather emotions ratings from UChicago Students for each face <br>
b. Survey methods <br>
-- Stratify survey (split the images up into 2 different surveys to make filling out each more manageable for survey respondants) <br>

### 3. AI Data 
a. Use DeepFace to estimate AI’s ‘perception’ of trustworthiness for the same faces shown in the survey <br>
b. Run emotion analysis 

## Overview of Analysis 

### 1. Data Wrangling and Cleaning 
### 2. Compare Deepface and Human Scores using the following fairness metrics:  <br>
-- a. Emotion Score Difference (deepface rating - human rating)  <br>
-- b. True Positive Rate <br>
-- c. Disparate Impact <br>
-- d. Agreement Rate<br>

------------------------------------------------------------

# Information on Reproducibility 

## 1. Link to our Quantitative Analysis 
-- i. Jupyter Notebook .ipynb: https://drive.google.com/file/d/1c3th46a2Um-dV82kLKxUCb-YzBDI4FeM/view?usp=drive_link<br>

## 2. Links to all of our Data 

### a. Fairface Data 
-- i. link to data: https://github.com/joojs/fairface <br>
-------- Scroll down to ‘Data’ Section <br>
------------Select ‘[Padding=0.25]’ <br>
-----------------Link: https://drive.google.com/file/d/1Z1RqRo0_JiavaZw2yzZG6WETdZQ8qX86/view?usp=sharing <br>
---------------------Within this zip file, we used fairface_label_train (link: https://drive.google.com/file/d/1OQsIEVj_ItTiaOxkpxaVtkt3qG8e-Asl/view?usp=drive_link) 

### b. Stratified Sample of Fairface Images
-- i. Stratified Sample of 56 Images was stored in a csv file <br>
--------- This is because the code to create this sample_df will result in different images everytime the code is run and we wanted to keep our selected images consistent through the project <br>
------------- Link to filtered images .csv: https://drive.google.com/file/d/1fF83Hd_7_8ZmmP7ESGLLxnAmd5xlfplI/view?usp=drive_link<br>

### c. Deepface Instructions AND Data 
-- i. Instructions to download Deepface module<br>
------- Go into terminal and type:<br>
----------- conda create -n deepface_env python=3.9 - let this run and then:<br>
----------- conda activate deepface_env<br>
------- Then still in terminal type:<br>
----------- conda install ipykernel<br>
------- let the above run and then type:<br>
----------- python -m ipykernel install --user --name deepface_env --display-name "Python (deepface_env)"<br>
------- Then open this jupyter notebook (relaunch anaconda) in the notebook, go to:<br>
----------- Kernel > Change Kernel > Python (deepface_env)<br>
------- Finally, run pip install deepface==0.0.91<br>
------- Then run the rest of the notebook and everything should work<br>

-- ii. Deepface Results Data <br>
-------- We stored our results from Deepface Emotion Analysis on our filitered images in a csv (link: https://drive.google.com/file/d/1nXASnVlB28fpI5zseo1jr3RIuJbcl6HA/view?usp=drive_link) <br>

### d. Qualtrics Survey Results <br>
-- i. We Stored our Survey Data in 2 csv files (one for survey A and one for survey B) <br>
-------- These results were merged in our jupyter notebook but were initially stored as 2 seperate csv's <br>
------------ link to survey A: https://drive.google.com/file/d/1k2P3YeQIVU40bcE36ZKeMZY-eVB9qLtV/view?usp=drive_link<br>
------------ link to survey B: https://drive.google.com/file/d/1YibfKZMVSwjFJ21Yt_yDi6S04oF9jevW/view?usp=drive_link<br>

# Final Deliverables of Our Project:

### 1. 1000 Summary Write-Up of our Project 
-- i. Link: insert link when done <br>

### 2. Project Poster Deliverable: 
-- i. Link: insert link when done<br>

### 3. Project Presentation Slides: 
-- i. Link: https://drive.google.com/file/d/1MrJvaLB-q-CCXXnMZl9wiafPGF-ZtVrm/view?usp=drive_link

### 4. Project Presentation Video: 
-- i. Link:

### 5. Quantitative Analysis (Jupyter Notebook): 
-- i. Jupyter Notebook PDF: https://drive.google.com/file/d/1shxF5tVBePCjoht55XvzJ7pAOGQnXLvN/view?usp=drive_link <br><br>
-- ii. Jupyter Notebook .ipynb: https://drive.google.com/file/d/1c3th46a2Um-dV82kLKxUCb-YzBDI4FeM/view?usp=drive_link<br><br>







