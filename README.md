The model file is large so it is uploaded to the gdrive
Model  files will be made public shortly

# Information

# Default Login Credentials
username - 'admin'
password - 'admin'

# Create a python3.12 virtual environment by executing command - 
python -m venv env

# Activate the environment by executing command
env\Scripts\activate

# After environment activation
# user can install all the requirement for this project by executing command
pip install -r requirements.txt

# User can run the project after installing the requirements
#  To run the project execute
python app.py

# All the images tested by users will be stored in `/static/images/test/` folder

# If the database is corrupted or not working just remove `/instance` folder and delete all the files
# in `/static/images/test/` folder and when the app is run next time it will create a database and then 
# create new accounts through frontend
# `Note : This above method will cost all the data already stored in the database handle with caution `

# Test samples is provided for testing or displaying 
# Test samples are in `/Test Samples` folder 
