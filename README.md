# Surfs Up
## Overview
This report is designed to analyze temperature trends for beachs in Oahu.  The database of information is stored in an SQLite database, [hawaii.sqlite](hawaii.sqlite), and extracted using SQLAlchemy.
## Results
The main results are two statistics tables on data from June and December.  Here are a few observations from those tables:
- The *average* temperatures for June and December were **74.9&deg;F** and **71.0&deg;F**, respectively.  These are fairly close numbers, showing that overall, the temperature can be expected to be relatively nice and consistent, which makes sense for a location relatively near the equator.
- The *standard deviation* of June and December were **3.26&deg;F** and **3.75&deg;F***, respectively.  These are also close, but do show a slight more variation in temperatures for December.  This can be confirmed by looking at the *interquartile range* - June's IQR only ranges from **73-77&deg;F**, while December's IQR ranges from **69-74&deg;F** -- not only a lower range, but wider by a degree.
- The minimum values for June and December tell what is likely the largest difference between the two months - though the averages are relatively close, the minimum for June is only **64&deg;F**, while December dipped down to **56&deg;F** at one point.  The maximum values of **85&deg;F** and **83&deg;F** are actually fairly close.  June doesn't get much hotter than December, but a December day has more potential to be cold.
## Summary
### Additional Queries - Stations
