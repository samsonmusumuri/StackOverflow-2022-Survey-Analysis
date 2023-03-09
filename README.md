### Table of Contents

1. [Installation](#installation)
2. [Objective](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

You must install plotly on your local machine to run certain plot functions .

Install the library using `pip`:

```
pip install plotly
```

## Objective<a name="motivation"></a>

By looking at the StackOverflow 2022 survey data I was curious to know:

1. What are the most popular websites for someone to start learning to code online and get certified?
2. Countries where the respondents are under the age of 18
3. What were the most in-demand developers as of 2022 according to our survey?
4. What does Organization Size looks like in 2022?
5. Where are these organizations located?

P.S I have used `gitly` library to display `plotly` plots as static. If you are running on your local machine then just installing plotly will work.

## File Descriptions <a name="files"></a>

There is a single notebook file `Stackoverflow_2022_Survey_Analysis.ipynb` that showcases the work relating to the aforementioned questions. 

The data folder consists two csv files `survey_results_public.csv` (Main survey results) and `survey_results_schema.csv` (Questions corresponding to each column in the main results csv) along with `so_survey_2022.pdf` which is the questionnaire.

## Results<a name="results"></a>

The descriptive analysis of the code can be found at [Medium](Paste_LINK_HERE).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Data is directly taken from [StackOverflow](https://insights.stackoverflow.com/survey/)

This database - The Public 2022 Stack Overflow Developer Survey Results - is made available under the Open Database License (ODbL): http://opendatacommons.org/licenses/odbl/1.0/. Any rights in individual contents of the database are licensed under the Database Contents License: http://opendatacommons.org/licenses/dbcl/1.0/
