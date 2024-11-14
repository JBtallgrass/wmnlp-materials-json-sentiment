#### Module 4 Requests, JSON, and basic NLP with spaCy

_Complete the tasks in the Python Notebook in this repository.
_To be submitted for credit, all changes must be committed and pushed to this repository (do not create your own repository unless instructed to on the course website)._

#### Rubric
_* (Question 1) Lyrics printed: 1 pt_
_* (Question 1) File created and submitted with notebook: 1 pt_
_* (Question 2) Correct polarity reported: 1 pt_
_* (Question 2) Question answered thoughtfully: 1 pt_
_* (Question 3) Function defined as specified: 1 pt_
_* (Question 3) Song lyrics retrieved and stored in separate files (0.5 pts/song): 2 pts_
_* (Question 4) Polarity scores printed (with appropriate label containing song title, .25 pts/song): 1 pt_
_* (Question 4) Questions answered thoughtfully: 2 pts_
 _____________________________________________________________________________________________________

# Jason A. Ballard

**Enterprise Data and AI Officer | Data Literacy Advocate | Educator in Professional Military Education**

Welcome! I'm Jason A. Ballard, an experienced data and AI integration leader currently serving as the Enterprise Data and AI Officer for Army University. My work bridges data science, AI strategy, and higher education, focusing on transforming decision-making through data literacy and innovation.

I invite you to explore my [GitHub repository](https://github.com/JBtallgrass), where I share insights, tools, and resources geared toward data literacy and advanced analytics in educational contexts. My projects emphasize practical solutions, open collaboration, and a commitment to enhancing data accessibility across teams.

## Key Areas of Focus
- **Data Strategy & Governance**: Developing frameworks that promote data-driven decision-making and cross-departmental data sharing.
- **AI & Analytics**: Leveraging data analytics and GenAI to unlock insights and drive transformational initiatives within Army University.
- **Data Literacy & Education**: Equipping leaders and students with data literacy skills critical for today's complex, data-rich environments.

Please don't hesitate to connect, collaborate, or contact me if our interests align. Let’s make data-driven transformation a reality together. 

## Linkedin: [Jason A. Ballard](https://linkedin.com/in/ballardjasona/) 

# Project Title: Module 4 Requests, JSON, and basic NLP with spaCy

## Project Overview
This is an academic project support the Masters of Science in Data Anlytics program at Northwest Missouri State University [NWMSU](https://www.nwmissouri.edu/academics/graduate/masters/data-analytics.htm)
The project supports requirements for the Web Mining and Natural Langauage Processing course. the following Learning Objectives: 
    At the end of this module students will be able to:

    1. Describe the characteristics of JSON. (CO3)
 
    2. Describe a basic Natural Language Processing Pipeline. (CO4)
 
    3. Access web-based APIs for data. (CO2, CO3)
 
    4. Apply basic NLP and visualize result. (CO3, CO5, CO6)

## Table of Contents
- [Overview](#project-overview)
- [Instructions] (#Instructions)
- [Features](#Features)
- [Requirements](#Requirements)
- [Installation](#installation)


## Instructions 
### Task 1. Get Started
Copy the base repository into your GitHub account by selecting the "Use this Template" button on GitHub and specifying yourself as the owner.  The base repository is available at: https://github.com/wmnlp-materials/json-sentimentLinks to an external site.
Clone YOUR new repo down to your machine.
 

### Task 2. Open Notebook and Complete Tasks 
On your machine, open the Jupyter Notebook for editing. 
Required: In your Markdown introduction, add a viewable, clickable link to your GitHub repo after your name. Build your brand and make your Markdown introduction clear and professional. 
Required: Use Markdown headings  (e.g. Question 1) to clearly show your content by each question number. 
Complete the first task.
Execute the notebook. Commit and push to GitHub. Verify your notebook appears correctly.
Complete the second task.
Execute the notebook. Commit and push to GitHub. Verify your notebook appears correctly.
Work this way until all tasks have been completed. 

### Task 3. Export to HTML and Finalize Repo
Execute each notebook.
After executing, export each notebook to HTML.
Commit and push your HTML files to your GitHub repo along with the executed notebooks. 
Verify you have a professional README.md that introduces your GitHub repository and provides helpful information about your project. 
Note: Your instructor may review just the notebooks - or just the HTML. Either way, notebooks are web pages, and we are learning to mine web pages. The more familiar you are with web pages, the easier it will be to get the information you need. 

## Features
- **Question 1**: 

- **Question 2**: 

- **Question 3**: 
Lyrics saved to love_story.pkl.
Lyrics saved to yellow.pkl.
Lyrics saved to hello.pkl.
Lyrics saved to shape_of_you.pkl.

Analyzing 'Love Story' by Taylor Swift:
Polarity score for lyrics in love_story.pkl: 0.049999999999999996
The polarity score for 'Love Story' by Taylor Swift is 0.049999999999999996

Analyzing 'Yellow' by Coldplay:
Polarity score for lyrics in yellow.pkl: 0.2430555555555556
The polarity score for 'Yellow' by Coldplay is 0.2430555555555556

Analyzing 'Hello' by Adele:
Polarity score for lyrics in hello.pkl: -0.14109195402298852
The polarity score for 'Hello' by Adele is -0.14109195402298852

Analyzing 'Shape of You' by Ed Sheeran:
Polarity score for lyrics in shape_of_you.pkl: 0.31929292929292935
The polarity score for 'Shape of You' by Ed Sheeran is 0.31929292929292935


## Requirements
    a. Markdown introduction with name and clickable link is required.
    b. Markdown Section Headings for each Question are required. 
    c. Execute your code before exporting HTML and pushing notebooks. (See FAQ for help.)  
    d. Unexecuted code is not eligible for credit.

### IMPORTANT: 

### Installation: 
```bash
python -m venv .env
.env\Scripts\activate
pip install -U pip setuptools wheel
pip install -U spacy
python -m spacy download en_core_web_sm
```
### Special thanks to: https://course.spacy.io/en/ 

[def]: #usage