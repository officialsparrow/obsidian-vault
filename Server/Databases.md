# Databases
Different databases for different data:
- Time series database for messages (e.g. [MongoDB](https://www.mongodb.com/), [InfluxDB](https://www.influxdata.com/))
```ad-question
Store pictures/videos inside or outside the database?
```
- OLTP database for users/groups/servers 
````ad-info
Database which holds the information about:
- users
- users' friends
- joined servers/groups of users
```ad-question
What kind of database?
Graph database, SQL Database
````