# Introduction
The design has 3 parts: spreadsheet, cloud function, actual loader. 
In order to make the connector work, you need to do the following steps.
## Step 0
Attach App Script project to GCP project. In order to do this, copy the project number from the GCP project, and insert it in Project settings -> Change project field
## Step 1
Copy script from file 'main.gs', as well as appscript.json (initially enabling appscript.json in configurations)
## Step 2
Create cloud function, triggered by the HTTP request, by coping script from file 'main.py', as well as requirements.txt
## Step 3
Replace the name of the function in the App Script code
## Step 4
Actual loader(python code) should be scheduled in Jenkins
