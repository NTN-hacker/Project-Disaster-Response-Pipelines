# Project: Disaster Response Pipeline

- I have enriched my knowledge and honed my data engineering skills through the comprehensive course I undertook. This enhanced expertise significantly broadens my horizons and unlocks my potential as a data scientist. In the pursuit of creating a model to power an API designed to categorize disaster-related messages, I am poised to leverage these acquired capabilities. My objective is to meticulously assess the disaster data sourced from Appen, drawing upon my newfound skills and insights, and to translate this into a practical and impactful project.

## Overview
My data science journey has come to an end with this project, where I have refined my data engineering abilities in addition to gaining new ones. This research is important for reasons other than just technical advancement, even if these abilities definitely increase my prospects and potential as a data scientist.
 
Fundamentally, our endeavor acts as a ray of hope during difficult times. It gives organizations and communities a strong tool to help them deal with catastrophic situations. Using the insights from catastrophe data gathered by Appen, the main goal of the project is to create a solid model for an API that categorizes disaster updates.

## Making A Transition
Understanding and classifying catastrophe communications in a methodical manner is essential in a society where natural and man-made disasters can occur at any time. This application's practical effects on the neighborhood and pertinent organizations are significant. To do this, follow these steps:

- **A prompt reply:** A well-functioning disaster message categorization system enables first responders and disaster management organizations to take action more quickly, resulting in the timely delivery of relief to people in need.

- **Allocation of Resources:** Resources may be distributed more wisely by classifying catastrophe messages appropriately. As a result, assistance may be directed where it is most needed, perhaps saving lives and time.
- **Involvement in the Community:** By giving people a venue to share knowledge during catastrophic occurrences, the initiative promotes community participation. The information gathered from the public may be very helpful for disaster management plans.
 
- **Decision Making Based on Data:** Through the processing and classification of large volumes of catastrophe data, this application facilitates data-driven decision making, which improves disaster response and mitigation tactics.

## Contribution
 
In addition to taking use of this project's capabilities, you are also helping to improve disaster response operations by using it. During times of crisis, the way you interact with the system may have a significant impact.

Please have a look at this initiative, become involved, and observe directly the potential effects it may have on disaster preparedness and response. We can work together to create a world that is better prepared and resilient.

This course has helped me acquire and hone my data engineering skills, which will expand my opportunities and potential as a data scientist. With the use of these abilities, I will evaluate Appen catastrophe data for this project in order to create a model for an API that categorizes disaster alerts.

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

## Github link
https://github.com/NTN-hacker/Project-Disaster-Response-Pipelines
