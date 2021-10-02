# CARTE Education Pathways

Chenyan Wang  
This repo is a clone of https://github.com/nelaturuk/education_pathways.  

## Lab 3 - Activity 1  
Screenshot of docker version.  
![alt text](imgs/lab3_1.jpg)  

## Lab 3 - Activity 2  
Screenshot of cloned repo and updated readme.  
![alt text](imgs/lab3_2_1.jpg)  
Readme: 
![alt text](imgs/lab3_2_2.jpg)  

## Lab 3 - Activity 3  
Screenshot of building the docker image.  
![alt text](imgs/lab3_3_1.jpg)  
Build log after docker image build is complete:  
![alt text](imgs/lab3_3_2.jpg)  

## Lab 3 - Activity 4  
Screenshot of the flask app running and the docker image.  
Flask app:  
![alt text](imgs/lab3_4_1.jpg)  
Docker image:  
![alt text](imgs/lab3_4_2.jpg)  

## Description
Welcome to CARTE's in-development tool for course selection at UofT. Education Pathways allows for more intelligent course searching, by matching not just the terms you search, but ones relevant to them. The more terms you search for, the more relevant your results will be! Even try searching across disciplines for the courses that best cover each.

Whatever year you are looking for, Education Pathways will also suggest courses in earlier years that will best help you to prepare. To get the most out of this, try searching for courses in a later year and see what is suggested for your current one.

We are looking for feedback to improve Education Pathways and make it more useful for students. If you have ideas or suggestions, please email us!

## Setup Instructions

### With Docker



## Repository files:

`./Procfile ./wsgi.py` *tells gunicorn how to run the program*

`./environment.yml  ./requirements.txt` *specifies python requirements for anaconda and pip respectively*

`./__init__.py` *main flask code*

`./readme.md` *this file*

`./resources:` *contains datasets used in the program*

`course_vectorizer.pickle df_processed.pickle`

`course_vectors.npz       graph.pickle`

`./static:` *contains any static elements of the webpage, in this case just the CARTE logo*
`CARTE_logo.jpg`

`./templates:` *contains flask templates for rendering HTML*

`_formhelpers.html course.html       index.html        results.html`
