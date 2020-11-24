# Project FIFA19 - FCB 2020

## Summary

In this project you should analyse data to attempt answering the following questions:

> Which are the best football teams according to individual player's `Overall` score?

> Can you identify relevant skills for each position (Attacker, Midfielder, Defender)?

> How are skills affected by age? Can you identify a skill that increases with age and another that decreases with age?

> Which player has the best combination of Dribbling and Finishing?

## Data

The FIFA 2019 datasets combine attributes from La Liga football players, including age, club, speed, dribbling, ball control, etc. The dataset is split into two files. The first CSV file is called `fifa_performance_statistics.csv` and contains performance statistics. The second CSV file is called `fifa_player_information.csv`. The original data files are available [here](https://www.kaggle.com/karangadiya/fifa19)

You should use the following two datasets:

1. The CSV file [fifa_performance_statistics.csv](fifa_performance_statistics.csv) downloaded from
[here](https://www.kaggle.com/karangadiya/fifa19) contains performance statistics, combining
data on players speed, dribbling, ball control, etc. from [La Liga](https://www.laliga.com/en-GB).

2. The CSV file [fifa_player_information.csv](fifa_player_information.csv) downloaded from
[here](https://www.kaggle.com/karangadiya/fifa19) contains information about football players,
including the club for which they play, age, height, weight, etc.
from [La Liga](https://www.laliga.com/en-GB).

## Deliverables

The GitHub repo for this project should contain, at least, the following files:

  * `index.Rmd`: R Markdown script with the R code doing the analysis of the data
    and the corresponding text explaining those analysis steps.
  * `index.html`: Resulting HTML output from processing (_knitting_) the file
    `index.Rmd`.
  * The CSV files employed during the analysis.
  * This `README.md` file.

The analysis of the data described in the HTML file should contain the following
sections:

  * **Abstract:** Summary of the question and the findings (max. 200 words).
  * **Introduction:** Description of the question and the data employed to answer it.
    Description of any steps taken, if any, previous to this R Markdown document,
    to prepare the data that is being analyzed.
  * **Results:** R code intertwined with text, descriping the analysis steps and the
    display items with the results, which should consist, **at least**, of one table
    and one plot.
  * **Conclusions:** summary of the findings, limitations of the study, ways in which
    this type of study could be improved in the future.
  * **References:** bibliographic references.

## Methodology

The analysis of the data should be carried out at least using R, but you can also
use shell or Python scripts to transform or prepare the data for the analysis with
R. If those prior steps using shell or Python scripts are included, they should be
described in the introduction section of the R Markdown document and, ideally,
made readily reproducible using a Makefile.

## Evaluation rubric

The rubric to evaluate this project consists of the following items:

* Have all members of the group made a sizeable number of commits to the GitHub repo?

* Does the GitHub repo contain at least the analysed CSV files along with the
  `index.Rmd` file and the resulting `index.html`?

* Does the R Markdown file `index.Rmd` run the analysis without errors and
  generates the expected `index.html` file?

* Does the analysis described in the resulting `index.html` file conform to
  the requested sectioning.

* Does the introduction explain clearly what is the question addressed, the
  data employed and the number of observations and variables involved?

* Do the plots show some meaningful summary of the data? Are axes in plots
  labeled in plain language and large enough to read?

* Does the GitHub repo include a _Makefile_ that automatizes the entire analysis
  pipeline and generation of the final report in the `index.html` file?
