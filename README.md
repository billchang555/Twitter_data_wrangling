# Twitter_dog_rates_Data_Wrangling

## Wrangle_report
This data wrangling process mainly contains five parts, which respectively are Gather, Assess, Clean, Reassessment and Save the csv.

## Gather
Three data sets have been gethered, which are Twitter_archive, Image_predictions and Twitter_JSON
Twitter_archive was downloaded in udacity website
Image_predictions - requests library was used to download the data, and then saved the csv in the local file system.
Twitter_JSON - also used requests library to download the data, then extract ID, retweet_count and favorite_count to form a dataframe

## Assess
Used both visual assessment and programmatical assessment, for visual assessment, mainly used df.info(), df.sample(), for programmatical assessment, mainly used for loop, df.value_counts(), indexing, df.duplicated() and so on, issues found in those data sets are as follows:
