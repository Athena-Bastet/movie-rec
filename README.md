# movie-rec
Movie Recommendation System using Collaborative Filtering.

Dataset:Movie Lens Dataset 100k
100,000 ratings (1-5) from 943 users on 1682 movies.

Each user has rated at least 20 movies.

Consists files such as u.data, u.info, u.item etc.

u.data     -- The full u data set, Users and items are numbered consecutively from 1.  The data is randomly ordered. This is a tab separated list of 
	                 user id | item id | rating | timestamp. 


Apache Spark:

Apache Spark is an open-source distributed general-purpose cluster-computing framework. MLlib and Ml are Spark's machine learning (ML) library.Its goal is to make practical machine learning scalable and easy.At a high level,it provides tools such as: ML Algorithms: common learning algorithms such as classification, regression, clustering, and collaborative filtering.

Spark provides an interface for programming entire clusters with implicit data parallelism and fault tolerance.It provides APIs in Java, Scala, Python and R.

org.apache.spark.mllib is the first of the two Spark APIs while org.apache.spark.ml is the new API.spark.mllib carries the original API built on top of RDDs.spark.ml contains higher-level API built on top of DataFrames for constructing ML pipelines.

Recommendation System:

Content-Based system
Focus on properties of items and preference of users
E.g.: If John likes Avengers: Age of Ultron, the system will recommend Doctor Strange, because they are fictional and produced by Marvel.

Collaborative-Filtering system
Focus on the relationship between users and items
Key point: people who liked similar items in the past will like similar items in the future
E.g.: Alice and Bob both like Tangled. The system knows Alice likes Shrek, so it guesses Bob will like this movie.


