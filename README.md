# Twitter profile @WeRateDogs wrangling data

In this project, I intend to use data wrangling techniques to clean and organize three sets of data, checking the main quality problems, and leading me to a more precise analysis at the end. Data wrangling is perhaps the most time-consuming process when analyzing data, so care must be taken and a well-defined process to implement it. In the first section, I will gather the three data sources, first df_twitter than a .txt file. According to df_api collected via api from twitter itself and collected programmatically. And lastly df_image_predictions is a .tsv file downloaded programmatically. In the second section I want to access the data, and discover quality and organization problems, as an objective, I intend to solve at least eight quality and two organization problems and list them, in section three, define them, program the necessary code and test. I will do this in each of the problems that I will encounter ahead.

In the fourth section I will try to analyze the data already organized and clean, and produce some insights and visualizations through graphs about the 3 sets of data already merged. The @dog_rates profile, also known as @WeRateDogs is a Twitter account that classifies the dogs of their owners in a funny way. @dog_rates has millions of followers and has achieved worldwide fame for its goal of entertaining its users. My goal is to analyze just over 5,000 profile tweets.

## Requiriments

### Python

- pandas==0.24.2
- numpy==1.20.0
- matplotlib==3.3.3
- seaborn 0.11.1
- requests
- json
- time
