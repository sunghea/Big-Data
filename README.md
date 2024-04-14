## practicing_parquet_colab.ipynb
Practicing Parquet - storing data in Parquet format and executing queries on Parquet data using Spark.

## practicing_partitions_colab.ipynb
Writing to Parquet - determine the differences in query execution time between a temporary view of an original Spark DataFrame, a parquet DataFrame, and a partitioned-parquet Spark DataFrame.

## flight_delays_cached_colab.ipynb
Caching Flight Delays -  import packages, create a Spark session, and set the shuffle partitions to 8.

## Delayed_Flights_temporary_view_colab.ipynb
Use Spark SQL to answer the following directions:
- Retrieve the first five airline carriers that arrive at George Bush Intercontinental Airport (IAH) in Houston and what airport the flight originates.
- Get all the origin and destination of all the Southwest (WN) flights.
- Get the airline carrier, the origin, the destination, and the elapsed time in descending order, and limit the results to 10.
- Get the total number of diverted flights from each airline carrier, and group the results by airline carrier and order by the total number of diverted flights in descending order.
- Get the average time for delayed departures and arrivals for each airline carrier, and group the results by the airline carrier.

## Olympic_analysis_colab.ipynb
Use Spark SQL to answer the following questions:
- How many new sports were played in the 2016 summer Olympics?
- What are the names of each sport that has been added?
- Which sports have been played since the first summer Olympics?
- Who are the top five athletes that won the most gold, silver, and bronze medals?

## basic pyspark with colab.ipynb
Follow the comments in the provided notebook to clean and display demographic data by using Spark DataFrames

## hot_days.py
Use MRJob to determine the total number of stations recording snow per date in Austin, Texas. Create mapper and reducer functions that return the total number of sta
