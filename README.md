# PROJECT TITLE

## i Business Case

Describe the business problem the model would solve, who the audience would be, predicted internal money saved or external revenue.
Include how this could be achieved by detailling what the y variable would be and the x variables (some examples are enough), where this information would be gathered from (comment on its quality), where the labelled data would come from (if applicable).
Detail the intended timeframe (rough estimates are appropriate) of deadlines for each stage from wrangling to final scripts.


## ii Table of Contents

- **1. File Discriptions**
- **2. Technologies Used**
- **3. Executive Summary**
	- [ ] [***3.1 Data Wrangling***](#3.1.1-dataset-x)
	- [ ] ***3.2 Exploratory Data Analysis***
	- [ ] ***3.3 Modelling***
	- [ ] ***3.4 Evaluation and Results***
	- [ ] ***3.5 Future Developments***
- **4. Final Scripts**

## 1 File Discriptions
<details><summary>show/hide</summary>

- [Data(Small)](): All datasets related to the project below 500 Mb in size.
	- Data\\[Cleaned](): Datasets preferablly fully wrangled ready for modelling work.
	- Data\\[Predicted](): Datasets including model predictions.
		- Data\Predicted\\[Assessments](): Datasets with model predictions based on assessment training sets.
		- Data\Predicted\\[Forecasts](): New datasets with final future predictions forcast by the final model at the end of the project.
	- Data\\[Raw](): The original datasets at the very beginning of the project.
- [Code](): All the code written in the project.
	- Code\\[Classes](): Bespoke python classes written for and used within the project scripts and notebooks.
	- Code\\[FinishedScripts](): Final python scripts abstracted from the project notebooks to enable model deployment.
	- Code\\[Notebooks](): All the jupyter notebooks for each stage of the project from Wrangling to Evaluation.

</details>
 
## 2 Technologies Used
<details><summary>show/hide</summary>

**Programming languages**
- SQL
- Python and Spark (Pyspark)

**Models Types**
- i.e. LASSO Regression (add link to resource on how this works)

**Azure resources** (add links to azure portal pages)
- Data Science Virtual Machine - DSVM
- Databricks Workspace - 
- Databricks Cluster - 
- Machine Learning Workspace -
- Kubernete(s) - 

**GitHub Repo** (add link to repo on GitHub)

</details>

## 3 Executive Summary
<details><summary>show/hide</summary>

Go over broader steps (20K ft) of project, concise desciptions of what was done and what was found for each.
Keep it conceptual not technical. README is for anyone not just teammates.
Include screen capture images for explanation.

### 3.1 Data Wrangling 
<details><summary>show/hide</summary>

([local](./code/Notebooks/3.1_Data_Wrangling.ipynb) or [GitHub]())

Flow of data through wrangling clean up. WHY?

#### 3.1.1 Dataset X
- 3.1.1.1 Dataset X Initial Data Checks

Dataset Schema

Dataset Summaries
 
- 3.1.2 Handle Dataset X Missing Data

Missing data in XYZ feature (variable) was discarded affecting n rows, k% of total. WHY?
Missing data in XYZ feature was imputed using TECH technique affecting n rows, k% of total. WHY?

- 3.1.3 Recode and Reformat Dataset X Features

This inconsistency was observed in XYZ categorical features, n rows were corrected this way.
DEF categorical feature was recoded for added ease of use.

**3.1.x Dataset Y**

same as for 3.1.1 etc

**3.1.x+1 Join Datasets**
**3.1.x+2 Deduplicate**

Dataset was ordered by XYZ features and deduplicated by IJK features removing n rows. WHY? 

</details>

### 3.2 Exploratory Data Analysis
### 3.3 Modelling
### 3.4 Evaluation and Results
### 3.5 Future Developments

- Short set of bullets describing next possible directions / actions for the project

</details>

## 4 Final Scripts
