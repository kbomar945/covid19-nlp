# Natural Language Processing on COVID-19 Twitter Data
### *HDAG Data Science Fellowship*

Our project aimed to characterize the public opinion of the COVID-19 pandemic by applying machine learning on COVID-related tweets. Our methodology is detailed below:

1. We queried the pre-curated dataset of COVID-related tweets published by [Chen et al.](https://doi.org/10.2196/19273) in *JMIR* for those tweets posted on July 1st, 2021. A total of 2,996,979 tweets were identified.

2. We filtered this initial dataset for tweets which were written in the English language and which were *not* retweets (i.e., were original content). The resulting 540,642 tweets were hydrated in Python using the Twitter API.

3. The 511,675 successfully hydrated tweets were parsed from JSON/HTML and cleaned in R, followed by feature extraction (e.g., hashtags, URLs, replies, retweets, location, etc.). 

4. Finally, we used natural language processing tools including structural topic modeling to derive aggregate features from our dataset.

Analyses were performed in Python and R. All code is available via our [GitHub repository](https://github.com/ayushnoori/covid19-nlp).
