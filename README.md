# Feature Engineering with Pandas


### Lesson Objectives
At the end of this lesson students will be able to:
- understand the purpose of feature engineering
- create new features from existing columns in pandas (string, numeric, and datetime formats)
- work with dates and times in pandas
- identify and handle missing values with Pandas
- clean data using a variety of Pandas techniques
- modify or create columns of a dataframe using the .apply() function
- implement .groupby() statements for segmented analysis.

The goal of feature engineering is simply to make your data better suited to the problem at hand. It is the process of using a combination of domain knowledge, creativity and the pre-existing columns of a dataset to create completely new columns.

Consider "apparent temperature" measures like the heat index and the wind chill. These quantities attempt to measure the perceived temperature to humans based on air temperature, humidity, and wind speed, things which we can measure directly. You could think of an apparent temperature as the result of a kind of feature engineering, an attempt to make the observed data more relevant to what we actually care about: how it actually feels outside!

You might perform feature engineering to:

- improve a model's predictive performance
- reduce computational or data needs
- improve interpretability of the results
