# (Baywheel)
## by (Mohamed Medhat)


## Dataset

> Provide basic information about your dataset in this section. If you selected your own dataset, make sure you note the source of your data and summarize any data wrangling steps that you performed before you started your exploration.

> The dataset selected is the Baywheel is coming from Lyft website, displaying the historical trips for a specific duration.
> the steps of wrangling were:
> Looking into the duplicates and null values.
> Assigning the variables to their respective data types.
> Looking into outliers data points in each variable.
> Looking into typo data or un-cleaned data points.

## Summary of Findings

> Summarize all of your findings from your exploration here, whether you plan on bringing them into your explanatory presentation or not.
> There were long trips data points which seems weird given the distribution of the trips across the hours-duration.
> Some of the locations were wrongly collected with un-realistic long/lat points.
> Some of the station names have a typo name.

> The relationship between trips and hours has a great relation in subscribers more than customers.
> There is a great trending between trips and hours across the month of each year.
> Most of the top 10 start stations are the same end ones which give us that the toppers stations are the hubs one which needs more focus.



## Key Insights for Presentation

> Select one or two main threads from your exploration to polish up for your presentation. Note any changes in design from your exploration step here.

> The top start and end stations are closely like together which give us more attention to this pattern as it will be considered as the huge hub of demanding trips and suppling also so we should align both demand and supply in the overlapping top stations from start to end, as some bikers will need bikes in same stations and also we need to ensure that there sustained bikes for the bikers in stations as well.


> The subscriber has a high trip per hour which need more focus on, as that means they can do more trips in one hour which need more supply to sustain their trips, given also they contribute much to the trips generation it might cause loss of trips for not fulfilling their trips.


## Resources:
https://stackoverflow.com/
https://www.kaggle.com/gemartin/load-data-reduce-memory-usage
https://pandas.pydata.org/docs/reference/general_functions.html
https://stackoverflow.com/questions/36288670/how-to-programmatically-generate-markdown-output-in-jupyter-notebooks
https://stackoverflow.com/questions/42818361/how-to-make-two-plots-side-by-side-using-python
https://matplotlib.org/devdocs/gallery/subplots_axes_and_figures/subplots_demo.html