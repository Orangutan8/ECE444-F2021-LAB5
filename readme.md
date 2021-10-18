Ian Sartor

This is a copy of https://github.com/nelaturuk/education_pathways

ACTIVITY 1:
![LAB5P1](https://user-images.githubusercontent.com/90578208/137650705-69a69b9c-af7a-4090-af7c-8cf81b9797ac.png)

ACTIVITY 2-5:
  HOME:
  ![LAB5HOME](https://user-images.githubusercontent.com/90578208/137650725-485e2492-cbc7-4d05-9c63-4205ae66216f.png)
  RESULTS:
  ![LAB5RESULTS](https://user-images.githubusercontent.com/90578208/137650732-8e7910c3-d693-4216-8a3f-a127d040cdc0.png)
  RESULTS TABLE:
  ![LAB5RESULTSTABLE](https://user-images.githubusercontent.com/90578208/137650744-8d450d51-540b-46e2-8460-96a57f866596.png)

ACTIVITY 6:
One important improvement by the styling is the readability. Previously the information on the page stretched to fit and tables were compressed. Both of these made the page more difficult and more broadly unpleasant to read. After the styling the page is more nicely spaced and compartmentalized, it is more obvious what the user is looking at, what they want to see is easier to locate.


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
