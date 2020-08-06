The primary objective of this lesson is to show how data from
spreadsheet-type applications can be loaded into R.

Instructions
------------

This lesson will use the following .Rmd files

1.  `skill-1-Import-Spreadsheet-Data.Rmd`
2.  `skill-2-Export-Spreadsheet-Data.Rmd`
3.  `skill-3-More-Data-Import-Examples.Rmd`
4.  `skill-4-Working-with-APIs.Rmd`
5.  `skill-5-Working-with-Databases.Rmd`

These files are located in the [skills
directory](https://github.com/aaronmams/rHD-skill-1-Data-Import/tree/master/skills)
with the project.

Additionally, there is a single .Rmd file in the [recipes]() directory:

1.  `Recipe-Build-a-Dataset.Rmd`

Contents
--------

### Code

This R code for this Skill is contained in the .Rmd files mentioned
above.

### Data

There are several "toy" data files provided for this lesson. They are:

1.  `flights_small.csv`
2.  `spotify-top50.csv`
3.  `xls-example.xlsx`
4.  `cocaine.sas7bdat`

The first two of these are comma separated value files that I obtained
from the data science platform [Kaggle](https://www.kaggle.com/).

The third is an excel workbook with some data I made-up for the purposes
of illustrating the `read_excel()` method.

The 4th is a SAS dataset I pulled from the
[priciplesofeconometrics.com](http://www.principlesofeconometrics.com/sas.htm)
website.

Lesson Narrative
----------------

If you care for some insight into why I made this our first lesson, it
is provided here. If this does not interest you and you wish to skip
this section nothing bad will happen.

There are two reasons why I chose to make this our first lesson. The
first is that, in my experience Social Scientists work with
spreadsheet-type data A LOT. Particularly within NMFS, I observe that
many of our research projects are centered around data that we have had
to collect (either by scraping the web, going to a data warehouse like
the St. Louis Fed, or conducting our own primary data collection). So I
see the task of getting data from a .csv file into R to be a near
universally important task for this group.

The second reason I have for leading off with this lesson is to try and
make things immediately "fun." I suppose fun is pretty subjective but I
suspect we all consider ourselves "data" people. And as "data" people, I
imagine that we would all rather be playing with real-life data than
talking about syntax or the difference between a vector and a list.

There will be some discussion in this course about data types and
structures. For this very first lesson however, I wanted to provide as
much of a feeling of accomplishment and excitement as I could.
