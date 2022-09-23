# Stack Explorer

## Inspiration

Both [Sheeza](https://github.com/sheezaaziz) and [Daman](https://github.com/Damans227) are Software Developers who often find it difficult to decide on a new technology stack when starting a new project. Like many other hackers out there, they also wonder: 

- What language has gained the most popularity over the years?
- What is the most commonly used programming language?
- What type of questions were asked on stack overflow ?
- What is the most widely used operating system ?

Rather than following random opinions posted online, they want to rely on fact based findings to choose a tech stack instead of following random online opinions. Therefore, they have come up witha solution called, Stack Explorer! 

## What it does

The Stack Explorer is a Jupyter-Lab notebook where we analyzed more than 3 million stackoverflow questions to understand latest trends in programming languages. We are happy to share our findings with everyone. 

## How we built it

As part of this project, we analyzed a stack overflow data set provided by Kaggle, and then broke the project down into the following steps: 

- Data Collection
- Data Cleaning
- Data Analysis
- Result Interpretation 
  
## Challenges we ran into

It was a challenging project for us. The following can be highlighted:
- We analyzed vast amounts of data (6 GB), so running analytics on such a large amount of data took longer than usual. 
- Decide what questions should be addressed during the data analysis phase. 
- Eliminating duplicate data from the dataset. 

## Accomplishments that we're proud of
Everything we did was an accomplishment, we made possible the functionality we imagined at the start of the project, in other words, our project rocks! 🎸

## What we learned
Our personal learnings are the following:
- Daman:
  - Python libraries, such as Matplotlib, Numpy, Pandas, Scatterplot. 
  - using jupyterLab Notebook and its git extension. 
  - using Github project board. 
  
## What's next for Stack Explorer
- Do a Machine Learning model that can answer questions such as **what language will become the most popular in 2025** or **could automatically classify stackoverflow questions using Natural Language Processing**. 

## Built With
<p align="center">
<img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/python/python-original.svg" alt="python" width="100" height="100"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/github/github-original-wordmark.svg" alt="go" width="200" height="100"/>
  <img src="https://miro.medium.com/max/1276/1*nQwgbHSXyLBfZht24QZLug.png" alt="go" width="100" height="100"/>
</p>

## How to run the app locally

Installation Requirements:
-  Python >= 3.8
- npm >= 12.0
- Pip3 >= 20
- Jupyter Lab >= 3.4.7

To run our Jupyter Lab Notebook, follow these steps:

 1. [Install Python 3](https://www.python.org/downloads/)
 2. [Create a virtual environment](https://docs.python.org/3/tutorial/venv.html#creating-virtual-environments) 
 3. [Activate the virtual environment](https://docs.python.org/3/tutorial/venv.html#creating-virtual-environments)
 4. Install Jupyter Lab:
 ```pip install jupyterlab```
 5. [Install Jupyter Lab-Git](https://github.com/jupyterlab/jupyterlab-git)
 6. [Generate a GitHub Personal Access Token](https://github.com/jupyterlab/jupyterlab-github/blob/master/README.md#2-getting-your-credentials-from-github)
 7. Run Jupyter Lab:
  ```jupyter lab ```
 8. Open the hosting url on your browser. The host link can be found on your terminal/command line after completing step 7.
 9. Download all import dependencies using:
  ```pip install <package-name>```
 10. [Download the "Train.csv" file](https://www.kaggle.com/competitions/facebook-recruiting-iii-keyword-extraction/data?select=Train.zip) to your local project directory. Note this single file is too large (2.35GB) to store on a GitHub repo.
 12. You should see a Jupyter Lab Notebook on the hosting link, as well as the git extension on the left hand panel of the web application. You can now use the git extension to commit changes on our notebook using its User-Interface, as opposed to the terminal/command line.

