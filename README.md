## Installation

### Getting a NYTimes key

Step 1. Obtain a nytimes api key. Then you need to put the key itself (secret not needed) in an otherwise blank `nytimes-apikey.txt` file.

### Installing jupyter and other dependencies

You will first need to install [poetry](https://python-poetry.org/docs/#installation). Then:

`poetry install`

## Running the notebook

First create a poetry subshell (accessing the virtual environment installed above):

`poetry shell`

Now in that subshell

`jupyter notebook`
