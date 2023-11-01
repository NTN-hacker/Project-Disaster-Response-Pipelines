# Project: Disaster Response Pipeline

- I have enriched my knowledge and honed my data engineering skills through the comprehensive course I undertook. This enhanced expertise significantly broadens my horizons and unlocks my potential as a data scientist. In the pursuit of creating a model to power an API designed to categorize disaster-related messages, I am poised to leverage these acquired capabilities. My objective is to meticulously assess the disaster data sourced from Appen, drawing upon my newfound skills and insights, and to translate this into a practical and impactful project.

## Project Structure:


	├── README.md
	├── app
	│   ├── run.py # The Flask file enclosed within this repository serves as the pivotal component responsible for executing the application
	│   └── template
	│       ├── go.html # Classification result page of web app
	│       └── master.html # Main page of web app
	├── data
	│   ├── Udacity-Project2.db # Database to save clean data
	│   ├── disaster_categories.csv # Input data to process
	│   ├── disaster_messages.csv # Input data to process
	│   └── process_data.py # ETL pipeline
	├── models
	│   └── train_classifier.py # ML pipeline
	│    └── classifier.pkl # Saved model. Please run the ML pipeline workplace to create this file.

## Instruction:

- In the project's root directory, you can kickstart the setup for your database and model by running the provided commands. These actions are critical for laying the groundwork and preparing the essential components needed to manage data and create your model effectively. Following these steps within the root directory ensures a smooth and efficient process, setting the stage for a productive project environment.

	+ To run ETL pipeline that cleans data and stores in database python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db
	+ To run ML pipeline that trains classifier and saves python models/train_classifier.py data/Udacity-Project2.db models/classifier.pkl
- Go to app directory: cd app

- Run your web app: python run.py

- Go to http://0.0.0.0:3000/
