# San Diego Water: E-Coli Bacteria Detection

<p align ="center">
<img src = "https://i0.wp.com/grapevine.is/wp-content/uploads/giphy-boiling-water.gif?fit=500%2C180&quality=99&ssl=1">
</p>

### Abstract 
The city of San Diego is looking to identify the presence of E-coli bacteria in the water supply. The company will provide recommendations to implement cost savings solutions.

### Problem Statement
E-coli “may be found in water sources, such as private wells, that have been contaminated with feces from infected humans or animals” (Centers for Disease Control and Prevention [CDC], 2015). The challenge is to provide recommendations on water treatment based on present E-coli bacteria to improve water quality for future residents.

### Goals 
Predictive Analytics: Predict E-Coli bacteria presence/likelihood (absent vs. non-absent)
Prescriptive Analytics: Identify cost effective solution to filter water in populated areas

### Non-Goals 
While we will endeavor to provide recommendations and viable solutions that hinge on sound and proper data analytics, it is not in our capacity to “fix” issues including but not limited to water shortage (quantity supplied), consistency, or temperature. 

### Data Sources 
Data will be stored on AWS service S3 Bucket that will communicate with AWS Sagemaker. The three files will be uploaded to S3 bucket.

All Drinking Water Tests (Bacteria): csv file with 68,032 entries and 9 columns
https://data.sandiego.gov/datasets/monitoring-of-indicator-bacteria-in-drinking-water/ 

Drinking Water Tests (Chemical): csv file with 18,306 entries and 8 columns
https://data.sandiego.gov/datasets/monitoring-of-select-chemical-parameters-in-drinking-water/ 

Effluent Water Tests (Chemical): csv file with 5,320 entries and 8 columns
https://data.sandiego.gov/datasets/monitoring-analytes-plant-effluent/ 
