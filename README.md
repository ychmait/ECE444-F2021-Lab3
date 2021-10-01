Youssef Chmait- This is a clone of https://github.com/nelaturuk/education_pathways for ECE444 Lab 3
Activities:
Activity 1:
![Activity 1](https://user-images.githubusercontent.com/90428846/135687794-9a75b039-15d3-4890-af5e-d7804a6dbad7.PNG)
Activity 2: 
![Activity 2](https://user-images.githubusercontent.com/90428846/135687832-e3cc9757-9bd9-4b57-9dca-b239e0cacd28.PNG)
![Activity 2-2](https://user-images.githubusercontent.com/90428846/135687863-9d0f23bc-6d7d-4236-9b87-0b0ede49c3a8.PNG)
Activity 3:
![Activity 3](https://user-images.githubusercontent.com/90428846/135687875-3265ba49-7b5f-41f6-8e72-f0f61ff457c3.PNG)
Activity 4:
![Activity 4](https://user-images.githubusercontent.com/90428846/135687900-1aae262d-0561-4379-bbf9-1cb2ae133a62.PNG)
![Activity 4-2](https://user-images.githubusercontent.com/90428846/135687909-d61892d4-83e9-41a0-a259-6af2f7aeb498.PNG)

Activity 5: 
Functional: Search bar does not allow certain tasks I wanted to do, such as searching by filter with an empty search bar, or allowing me to search across more than one course-level at a time. I would add these features to improve it.
Non-functional: I had to try mutliple browsers before I could get the site to display search results, and in the end the only browser that worked was Internet Explorer. I suspect there was a compatibility issue with the plugins/popup settings of my main browsers. To improve the tool, I would investigate the cause of this issue to make the website more accessible to people using different browsers/plugins.
# CARTE Education Pathways

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
