# Data-259-Group-Project
Aalia Sait, Ayesha Ramnani, George Lin 

# Face-Off: Human and AI Emotion Perception

Our project aims to investigate the question: <br>
How do human judgments of facial emotions vary across race and gender, and to what extent do facial analysis models reflect or amplify these biases in their own predictions?

## Overview of Qualitative Methods: 

### 1. Literature Review 
a. Analyze key literature for background research and to motivate our research question
b. Analyze specific papers on ethical risks for the discussion section of our project and to support quantitative results 
c. Gather key statistics or evidence to cite in our research paper 

## Overview of Quantitative Methods: 

### 1. Data Collection  
a. Use the FairFace dataset.  It includes labeled data for race, gender, age. <br>
-- Download the FairFace CSV + images <br>
-- Filter and sample images to make sure there is demographic diversity <br>
-- Then select 55 unique images (enough for analysis, but not overwhelming for survey takers – maybe try to figure out what an optimal number of images for survey is from a source online) <br>

### 2. Human Survey 
a. Use Qualtrics to build a survey to gather emotions ratings from people for each face <br>
-- Ex: for each face, ask a question like: <br>
----- “On a scale from 0 (not angry) to 100% (very angry), how does this person appear to you?” **We can add happy and neutral as well to align with the DeepFace metrics <br>
b. Survey methods <br>
-- Stratify survey (split the images up into 2 different surveys to make filling out each more manageable for survey respondants) <br>

### 3. AI Data 
a. Use DeepFace to estimate AI’s ‘perception’ of trustworthiness for the same faces shown in the survey <br>
b. Run emotion analysis <br>
-- Outlined in the DeepFace Implementation Document <br>

## Overview of Analysis 

### 1. Initial Analysis 
a. Get average trust ratings by demographic group for AI and human <br>
b. For human: <br>
-- Match trust ratings to image IDs and demographics <br>
-- Compute mean and standard deviation of ratings per image <br>
-- Compute Average trust score by race, gender, and race × gender <br>
c. For AI: <br>
-- For each image, match the DeepFace trust score to demographic labels <br>
-- Compute mean and standard deviation of ratings per image <br>
-- Compute Average trust score by race, gender, and race × gender <br>

### 2. Comparitive Analysis Initial Overview 
a. For each image: compare human mean rating vs. AI trust score
-- Compute Pearson/Spearman correlation
b. Group bias comparison:
-- Plot bar charts side-by-side:
c. Average Human Rating vs. AI Score per Demographic Group
-- Identify groups where:
---- AI and human both rate lower (possible reinforced bias)
---- AI rates higher/lower than human (possible divergence)
d.  Bias gap:
-- For each group, compute the difference between AI and human trust scores



