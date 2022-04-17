# Impacting the Business with a Distributed Data Science Pipeline - MSADS508: Cloud Computing  
## San Diego Street Conditions Classification  
## Completed: 04/17/2022  

<p align ="center">
<img src = "/images/IMG_0037-ANIMATION.gif" width = "50%" height = "auto">
</p>

### Installation

To use this project, first clone the repo on your device using the commands below:

`git init`

`git clone https://github.com/lshpaner/sd_streets.git`

### Partner(s)/Contributor(s)  
**Authors:**  
* [Leonid Shpaner](https://github.com/lshpaner)  
* [Jose Luis Estrada](https://github.com/jose-luis-estrada)  
* [Kiran Singh](https://github.com/kiransingh789)  
**Company Name:** Street Infrastructure Solutions (SIS)  
**Company Industry:** Streets Infrastructure/Transportation  
**Company Size:** 3 (startup)

### Methods  
* Data Exploration  
* Pre-processing  
* Data Visualization  
* Statistical modeling  
* Data modeling metrics  

### Technologies  
* Python (AWS Sagemaker)  
* SQL Transformations  
* AWS (Sagemaker, Athena, S3)  
* Powerpoint  
* Word  
* Excel  

### Abstract 
The city of San Diego has become reliant upon a streets Overall Condition Index (OCI) that was designed and implemented by the United States Army Corps of Engineers. The company will provide recommendations to implement cost savings solutions.

### Problem Statement
The city of San Diego has decided to "spend $700,000 to survey the condition of every street in the city so repairs and upgrades can be geared toward increasing social equity, fixing many long-neglected roads and boosting opportunities for bicycling" (Garrick, 2021). The challenge is to identify viable targets (streets) for future infrastructure projects for the city of San Diego. A high caliber consulting service that our company provides is instrumental for handling the following task. Classification of streets in above par conditions is a crucial step in establishing project feasibility. The city's future depends on it.

### Goals 
1. Predictive Analytics: Predict street viability presence/likelihood (good/fair vs. poor)
2. Prescriptive Analytics: Identify cost effective solution to expand infrastructure projects
3. Informative: Inform City of San Diego of the outcome in a timely manner (by 5/18/2022)


### Non-Goals 
While we will endeavor to provide recommendations and viable solutions that hinge on sound and proper data analytics, it is not in our capacity to “fix” issues including but not limited to traffic, parking meters, or real-estate assets or valuation.

### Data Sources 
Data will be stored on AWS service S3 Bucket that will communicate with AWS Sagemaker. The three files will be uploaded to S3 bucket.

* Streets Overall Condition Index (OCI): csv file 30,712 entries and 12 columns  
https://data.sandiego.gov/datasets/streets-overall-condition-index/

* Street Repair Projects: csv file with 23,433 entries and 19 columns  
https://data.sandiego.gov/datasets/streets-repair-projects/

* Traffic Volumes: csv file with 12,432 entries and 10 columns  
https://data.sandiego.gov/datasets/traffic-volumes/


### References
Garrick, D. (2021, September 12). San Diego to spend $700K assessing street conditions to spend repair money wisely. *The San Diego Union-Tribune.* https://www.sandiegouniontribune.com/news/politics/story/2021-09-12/san-diego-to-spend-700k-assessing-street-conditions-to-spend-repair-money-wisely

## Presentations and projects  
* [Amazon SageMaker (AWS) Python - Jupyter Notebook](https://github.com/lshpaner/sd_streets/blob/main/sd_streets.ipynb)  
* Presentation  