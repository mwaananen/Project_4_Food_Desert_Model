# Project_4_Food_Desert_Model
+ Mark R. Waananen
+ Crystal Rosenbrook
+ Joanna DeLaune
+ Mike Wellnitz

## Research Question
Despite considering multiple topics to build our model around, including personal beverage choices, sports analytics, diagnostic medical data, air quality data, and other weather, or natural disaster data, we elected to build out a model around census data that specifcally concerns food accessability. As a group we agreed that an easily accessible, single source dataset, would offer the simplest route to quickly building a model. You can find the dataset we chose at [USDA Economic Research Service](https://www.ers.usda.gov/data-products/food-access-research-atlas/download-the-data/) site, "Food Access Research Atlas Data Download 2019."

_Can we create a model using census tract data that could be used to predict food deserts in Minnesota?_

## Data Cleaning
The Excel file was downloaded and resaved as a CSV, before being cleaned in Jupyter Notebooks. From here the data was cleaned using the Pandas library, before coding our model, using the same Jupyter Notebooks file.

### Languages and Libraries
+ Excel
+ Jupyter Notebooks
+ pandas
+ matplotlib
+ tensorflow
+ sklearn
  + StandardScaler
  + train_test_split

## Creating the Model
Once the dataset and all its data points were understood and determined to be of value to building the model. Some of our group began cleaning and filtering the data. These same group memebers took it upon themselves to make a first attempt to build an intial model. Their attempt, with feedback from an outside source (tutor), ran much accurately than anticipated. In the following session, the group agreed that some considerations regarding the data needed to be addressed. This was reinforced when we presented our current model to our supervisor (instructor Shaun). In response we adjusted our data and re-ran our model anticipating some type of change. The model ran very slightly more accurately after this attempt and as a group we concluded this satisified the task requirements and that we had successfully built a model that answered our research question.

### Final Visualizations
The code concludes with a final visualization. The epochs range plot tracks the training loss over the amount of epochs that are run in the previous code. This visualization helps determine if were are using the coorect approx. amount of epochs in our code, and if the model is either overfitting, or underfitting the data.

## Insights
The genesis of this group's project was whether the group was able to create an accurate model that could, in theory, be used by policy makers and community organizers to address the prevelance of statewide food deserts and food insecurity more broadly. We feel confident that we achieved this objective. However, we uderstand that we have not yet fully tested the bounds and capability of the model. In the future we would endeavour to test the model using different variables from the same dataset, or perhaps even entirely different datasets altogether. How the model could be deployed in the future depends directly on the limits of the model is capable of. 

### Presentation link
Presenting our model and full project using [Pitch.com](https://pitch.com/public/fc6269ec-781e-48f8-a2d0-75a37ff92843)

### References
+ USDA Dataset (see above)
+ USDA [Documentation](https://www.ers.usda.gov/data-products/food-access-research-atlas/documentation/)
+ GitLab Class Files
+ ChatGPT 

