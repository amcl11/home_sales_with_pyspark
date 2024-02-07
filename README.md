# Module 22: 

## `home_sales` w/ PySpark 

In this challenge, we used SparkSQL to determine key metrics about home sales data. Using Spark, we will create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

**Runtime questions answered:**

 - Uncached data query runtime: `1.656`  
 - Cached query runtime: `0.973`  
 - Paritioned query runtime: `0.858`

### Conclusion:

**Uncached query runtime:** Represents the baseline, where data is read directly from its source, leading to slower access due to disk I/O.

**Cached query runtime:** Caching improves speed by storing data in memory, enabling quicker access than disk reads.

**Partitioned query runtime:** The fastest runtime, as partitioning reduces the volume of data scanned per query, enhancing efficiency.

The transition from uncached to cached and then to partitioned data illustrates the benefits of in-memory data access and efficient data scanning through partitioning.


