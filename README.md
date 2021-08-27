This project is an exploration into visualizing large news stories over time. Currently, I am exploring how I might identify the level of importance, or at least popularity, that a particular news story had. In time, this might grow to aggregate news from various sources (probably a more difficult problem). Hopefully, this feeds into a timeline visualization that affords exploration and a more keen sense of our hectic history.

Motivated by recent trends with certain political factions trying to rewrite history, I hope to present a clean record of what actually happened to get us where we are today.

## Installation

### Getting a NYTimes key

Step 1. Obtain a nytimes api key. Then you need to put the key itself (secret not needed) in an otherwise blank `nytimes-apikey.txt` file in the root directory of this project.

### Installing jupyter and other dependencies

You will first need to install [poetry](https://python-poetry.org/docs/#installation). Then:

`poetry install`

## Running the notebook

First create a poetry subshell (accessing the virtual environment installed above):

`poetry shell`

Now in that subshell

`jupyter notebook`
