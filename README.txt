Made the following changes in the deploy.py file to make it executable from CLI and through gitHub action.
- Changes raw_input path to /demo/dlt_loan
- Commented the 'dbutils' lines as it can not be run through CLI
- Added DATABRICKS_HOST and DATABRICKS_TOKEN of the workspace where I wanted to run this project to create DLT pipeline

Execute 
python deploy.py 