# Delta Table

1. Data is stored in Parquet files in Data Lake
2. On top Delta Logs records each trasnsaction as a new commit.
3. The current state is maintained by these trsnsaction logs.
4. If a record is added a new commit is made in transaction log.
5. To purge deleted enetries, use vaccum command.
6. By default retention of data is 7 days allowing 7 days of travel time.
7. 
