# absolutetrash

## An exploration of flytipping in Birmingham
![Histogram](assets/flytipping1.jpeg)

Using publicly available datasets on fly-tipping I have conducted exploratory data analysis then built a time series analysis based on two datasets for incidents reported in Birmingham, and one dataset for all incidents reported nationally using Python. The data shows that fly-tipping has increased nationally, not just in Birmingham, although as a member of the community here I had anticipated that the anecdotal rise in fly-tipping incidents was a result of bin strikes. _ Expand on: Larger UK issue that needs tackling_

## Data Sources

[Monthly data for fly-tipping incidents in Birmingham was obtained and consolidated from mysociety](https://github.com/mysociety/fms_geographic_data/tree/master)

mysociety operates fixmystreet.com, a website where citizens can report fly-tipping incidents, amongst other local issues.

[Yearly data for fly-tipping incidents across the UK was obtained from gov.uk](https://www.gov.uk/government/statistics/fly-tipping-in-england).

The UK government publishes a wide variety of statistical data, fly-tipping data is collected from local authorities.

## Data Cleaning

Very little data cleansing was required as the data has been aggregated and both organisations provide background information on their methodologies which show consistency in data collection and cleansing. 

No nulls were detected in gov.uk data using Power Query's column profiling:

<img src="/assets/PQ - LA data - No null.png" alt="Power Query No Null gov.uk">

Some errors were detected in the total number of incidents for certain regions/years. There were 21 rows with errors of a total of 2930 rows of data (<1%), and so the errors were removed rather than replaced. The datset is large enough to be viable without these 21 rows:

<img src="/assets/PQ - error with total incidents - LA.png">

However once resolved there were no further issues with the fixmystreet.com data:

<img src="/assets/PQ FMS no null.png">

Duplicated reports are not able to be identified from these aggregated datasets and so we are reliant on the methodologies used by mysociety and the UK government.

## EDA

Exploratory data analysis was conducted in PowerBI

[Graphs]

## Time Series Analysis

[Time Series in Python](https://github.com/ducksinarowdata/absolutetrash/blob/main/Flytipping_Summative.ipynb)

```
```

```
```

```
```

[Images of TS graph]

## Results

## Key Takeaways


