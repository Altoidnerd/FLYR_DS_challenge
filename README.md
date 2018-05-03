# FLYR_DS_challenge

My recently completed data scientist employment screening "homework exercise."



## Getting Started

I had to cut search_data.csv in two and zip them separately to get around github's filesize limit.  Run the following to generate search_data.csv


```
me@shell $ unzip search_data_1.zip && unzip search_data_2.zip && cat search_data_1.csv search_data_2.csv > search_data.csv && du -h
```

The output should look like 

```
search_data.csv
Archive:  search_data_1.zip
  inflating: search_data_1.csv
Archive:  search_data_2.zip
  inflating: search_data_2.csv
581M	search_data.csv
```

You should be ready to go.

```
me@shell $ jupyter notebook fare_regression.ipynb &
me@shell $ jupyter notebook booking_classifier.ipynb &
```
