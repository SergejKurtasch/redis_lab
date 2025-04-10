Redis Lab: Querying the Movies Dataset
Objective
This lab will help you practice querying data in Redis using the dataset provided here. You will execute a series of progressively challenging queries to retrieve, filter, and manipulate movie-related data.

Dataset Overview
The dataset consists of the following key types:

Movies: Stored as hashes with keys like movie:<id>
Theaters: Stored as hashes with keys like theater:<id>
Users: Stored as hashes with keys like user:<id>
Ratings: Stored as sorted sets to track movie ratings
Indexes: Secondary indexes to facilitate searching
