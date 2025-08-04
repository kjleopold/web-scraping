# Web Scraping and NLP with Requests, BeautifulSoup, and spaCy

Complete the tasks in the Python Notebook in this repository.
Make sure to add and push the pkl or text file of your scraped html (this is specified in the notebook)

## Rubric

* (Question 1) Article html stored in separate file that is committed and pushed: 1 pt
* (Question 2) Article text is correct: 1 pt
* (Question 3) Correct (or equivalent in the case of multiple tokens with same frequency) tokens printed: 1 pt
* (Question 4) Correct (or equivalent in the case of multiple lemmas with same frequency) lemmas printed: 1 pt
* (Question 5) Correct scores for first sentence printed: 2 pts (1 / function)
* (Question 6) Histogram shown with appropriate labelling: 1 pt
* (Question 7) Histogram shown with appropriate labelling: 1 pt
* (Question 8) Thoughtful answer provided: 1 pt

## Objective
This exercise illustrates how to access web-hosted APIs, get back a response in JSON to an external site. format, and extract the information we need from the JSON. Accessing APIs is a key skill for data analysts. APIs are used to get stock data, weather data, and much more. This project used an API to access song lyrics or poems. The specific API used isn't important, there are many and they often change. The goal is to be able to (a) make an API request and (b) find the information needed in the returned response.

### Step 1: Fork the base repo and copy to local machine
* Fork [Base Repository](https://github.com/wmnlp-materials/web-scraping)
* `git clone` [(https://github.com/kjleopold/web-scraping)](https://github.com/kjleopold/web-scraping)

### Step 2: Set Up and Activate Virtual Environment
* `python -m venv .venv`
* `.venv/Scripts/activate`
* Select appropriate interpreter
    - Ctrl + Shift + P
    - Python: Select Inerpreter
    - Choose .venv\Scripts\python.exe

### Create .gitignore and Install Packages
* Create .gitignore.
* Create requirements.txt to install packages.
* `pip install -r requirements.txt`

### Open Notebook and Complete Tasks
* Make sure kernel is selected.
* Add a viewable, clickable link to GitHub repo after name in the Markdown Introduction.
* Use Markdown headings to show content by each question number.
* Complete the questions.

### Execute the notebook

### Commit and push to GitHub
* `git add .`
* `git commit -m "Meaningful comment"`
* `git push`
* Verify the notebook appears correctly in GitHub.

### Export to HTML and Finalize Repo
* `!jupyter nbconvert --to html web-scraping.ipynb`
