# The state of DevOps

This is the repository for my analysis on developer sentiment towards DevOps with
the [Stack Overflow 2020 Developer Survey](https://insights.stackoverflow.com/survey) data. Take a look at
my [blog post](https://bewagner.net/programming/2021/06/01/stackoverflow-developer-survey/) for the full analysis.

## Motivation

The aim of this repository is a data analysis according to the CRISP-DM data science project model. I chose the Stack
Overflow 2020 Developer Survey because it contains data about developer sentiment towards DevOps.

DevOps is an important topic in the software development world. For some time it got quite some hype. I was interested
in whether this has lead to widespread adoption and how developers feel about the topic. 

## Dependencies

The Python code for the analysis can be found in `Developer survey blog post.ipynb`. It uses the `pandas` library to
transform and visualize the data. You can install it via

```commandline
pip install pandas
```

## Files in this repository

- `Developer survey blog post.ipynb`
  Notebook file that contains the data analysis
- `survey_results_public.csv.zip`
  Data I downloaded from the Stack Overflow Developer Survey site
- `plotX.png/.svg`
  Image files for the plots used in the blog post

## Summary of the results

The analysis tries to answer the following questions:

- Do people only recognize the value of DevOps once they have it?
- How does having DevOps impact job satisfaction?
- How does sentiment towards DevOps change with company size?

We see that there is a clear indication that developers recognize DevOps importance once they worked with it. In the
data we analysed, DevOps does not seem to have an impact on job satisfaction. Finally, we see that the majority of
developers see DevOps as an important tool in a modern software organization. Only respondents from companies with less
than ten employees see it as less important.





