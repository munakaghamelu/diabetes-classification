# Diabetes Classification Model using Logistic Regression
It is estimated that 415 million people are living with diabetes in the world, which is estimated to be 1 in 11 of the world's adult population. 46% of people with diabetes are undiagnosed.

As part of the Coders of Colour Computer Vision course we were taught about many different machine learning algorithms and how they can be used to solve real world problems. For the classification practical I chose to explore a diabetes dataset containing the most common symptoms of a diabetic. My model was able to figure out that 'Polyuria' and 'Polydisia' were the most common indicators of having diabetes and use that information to balance the dataset. It was then able to predict whether someone was diabetes with an accuracy of 78%.

The approach I took to solve this task was:
<ol>
  <li>Retrieve my dataset.</li>
  <li>Preprocess and Visualize data.</li>
  <li>Apply Logistic Regression model.</li>
  <li>Produce model, and see how well it predicts using metrics such as confusion matrix.</li>
</ol>

The python libraries I used were pandas, numpy, sklearn, seaborn and matplotlib. 

## Dataset ##
Data uploaded to AWS S3 - https://diabetes-data-mka.s3.eu-west-2.amazonaws.com/diabetes_data_upload.csv

## Setup ##

All requirements are within the Jupyter Notebook. You just have to have a pytorch virtual environment setup, or can load the notebook into Google Colabs.

<!--## Usage ##
<!-- Run the game by running tetris.py
```
python tetris.py
```
<br />To DISABLE the autoplayer, go to `te_settings.py`and set the boolean variable `DEFAULT_AUTOPLAY` to `false`
<br />Controls:
<br />`a`- Move Left
<br />`s`- Move Right
<br />`k`- Rotate Left
<br />`l`- Rotate Right
<br />`space`- Hard drop
<br /><strong>Compatibility: python version 3.7.0 or later</strong> -->
