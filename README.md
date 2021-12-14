# covid-twitter-mask-sentiment-statistical-analysis
Statistical analysis suite featured in the [paper](https://www.medrxiv.org/content/10.1101/2020.08.28.20183863v3): Unmasking the conversation on masks: Natural language processing for topical sentiment analysis of COVID-19 Twitter discourse (September 2020)
## Background
This notebook houses a series of statistical procedures used to analyze a dataset of Tweets with associated sentiment scores. 

Written as part of a sentiment analysis pipeline which was used in the Summer of 2020 to analyze public sentiment related to masks, as described in the associated [paper](https://www.medrxiv.org/content/10.1101/2020.08.28.20183863v3) for the project. 

The original conceptualization of the Twitter data extraction pipeline used to acquire the data for this analysis, as well as the motivations for the data acquisition, is described in the [project repository](https://github.com/TheRensselaerIDEA/COVID-Twitter) from the RPI Institute for Data Exploration and Applications (IDEA). Those interested in regenerating the Tweet dataset decribed in the paper should see the [paper repository](https://github.com/TheRensselaerIDEA/COVID-masks-nlp) for a guide to setting up the data collection and analysis pipeline.

## Setup
This notebook is best run in a knitr-enabled R environment; I recommend RStudio. The code itself can be run in any R environment.
