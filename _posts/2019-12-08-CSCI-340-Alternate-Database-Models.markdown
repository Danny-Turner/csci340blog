---
layout: post
author: Dan Turner
---
As part of our coursework, everyone in class was assigned to learn an alternate database model to present in class. I was on the team that learned InfluxDB. InfluxDB is a specialized database designed to work with time series data. Other members of the class gave presentations on the five databases below.

##### Cassandra
Primarily designed to prevent data loss. The database automatically stores multiple copies of all data to minimize the chance that any data could be lost.

##### MongoDB
Object Oriented database. This seems very similar to the way most of the frameworks we have seen interact with databases. In particular, the frameworks use objects (models) to interact with tables. MongoDB seems to eliminate the middle step of creating a model and simply stores the data as objects to start with.

##### QGIS/PostGIS
Spatial/Map database. This is a very specialized database with a very nice interface for working with maps and geographical data.

##### REDIS
In memory database. Uses key-value design and is very fast since all data is kept in RAM instead of stored on a physical disk. Needs to be used in conjunction with another database to store and retrieve information on a long term basis.

##### Neo4j
Graph database. Instead of using tables it uses nodes and relationships.
