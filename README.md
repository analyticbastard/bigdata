## Nature of data processing

In the big data world, you’re either doing batch analytics where nobody really cares about query time (most businesses); or you’re doing streaming (Uber, Facebook and kin) where query time is critical, but data is only big on aggregate — each user only sees or uses a tiny bit and there are batch jobs going on in the background.
[4 fails and a win in big data](https://towardsdatascience.com/four-fails-and-a-win-at-a-big-data-stack-for-realtime-analytics-4f82f651d476)

From the above link (realtime use case):
- Table normalization, slows down joins
- Apache Spark: not truly realtime
- Solution: Python/Pandas/Dask


# Use cases

[6 Big Data use cases in banking](http://www.ingrammicroadvisor.com/data-center/5-big-data-use-cases-in-banking-and-financial-services)

## Generic use case! 

- Website optimization (navigational info)
- Campaign turnover
- Campaign design (market segmentation)


# Databases

## SQL for Big Data

- PostgresQL sharded
- Apache Presto
- Hive

## NoSQL

- Cassandra
- MongoDB
- Elasticsearch
- Neo4J: Graph database

# Processing

## Batch

- Hadoop
- Spark

## Stream

- Storm
- Kafka
- Samza
- Flink

## Queuing systems

- RabbitMQ (AMPQ protocol)

## Serialization formats

- Apache Avro
- Apache Parquet
- JSON and CSV
- Protocol buffers
- SOAP
- Apache Thrift
- XML
- Yaml


# Monitoring

- Splunk
- Kibana/Logstash
- Rieman


# Geospatial data (GIS)

- PostGIS Postgres plugin
- Manifold GIS [course](https://www.udemy.com/big-data-and-gis/)
- [Big data and GIS](https://www.redlands.edu/globalassets/depts/school-of-business/gisab/workshops-conferences/namchul-shin-slides---research-opportunities-in-sptial-big-data-location-and-analytics-12-6-15.pdf)
- [Shapefiles and GeoJSON](https://blog.exploratory.io/creating-geojson-out-of-shapefile-in-r-40bc0005857d)
- [NY taxi data](https://medium.com/@shivendranitb/time-series-analysis-new-york-taxi-data-260-gb-9f9576842b89)



# Machine learning

## Fundamentals of Statistics

- Random variables
  -  Real and vector RVs
  -  Distributions, moments (variance) and entropy
  -  Conditional probablity
- Statistical independence: What can be forecasted
  -  X^2 test
- Linearity and non-linearity
- Feature engineering and multicollinearity
- Statistical assumptions and hypotheses in models

## Model inference

- Regression
  - Linear least squares, ANOVA
  - Support Vector Regression (SVR)
- Classification
  - k-NN -depending on distance-
  - Support Vector Machine (SVM)
- Clustering
  - k-means
- Outlier detection
  - [z-Scores](https://www.knime.com/blog/four-techniques-for-outlier-detection)
  - [Isolation forest](https://www.knime.com/blog/four-techniques-for-outlier-detection)
  - nu-SVM
- Dimensionality Reduction
  - Principal Components Analysis (PCA)
  - Others: ICA, t-SNE

![](https://cdn-images-1.medium.com/max/1000/1*dYgEs2roROf3j2ANzkDHMA.png)

## Feature engineering

Context-dependent, Expert knowledge

## Neural networks

- For regression: (Deep) Feed forward, RBF...
- For dimensionality reduction: autoencoder
- Training algorithms: Backpropagation, Dropout...

![](https://cdn-images-1.medium.com/max/1000/1*gccuMDV8fXjcvz1RSk4kgQ.png)

## Machine learning cheatsheet
[Link](https://becominghuman.ai/cheat-sheets-for-ai-neural-networks-machine-learning-deep-learning-big-data-678c51b4b463)

![](https://cdn-images-1.medium.com/max/1600/1*tEo4x2-2iOZcnhSF13rUTA.png)


## Natural Language Processing

- Python's [NLTK](http://www.nltk.org/book/)
- [Others](https://elitedatascience.com/python-nlp-libraries)
- Web scrapping
- Other feeds
- Sentiment analysis

# Data scaling and Sysadmin

- On premise
- Cloud

## Docker containers

## Container orchestrators

- Puppet
- Kubernetes

## Coordinators

- Zookeeper

## Amazon cloud

- Kinesis streaming data ingestion
- Redshift (column-oriented modified Postgres 8.0.2)
- S3: Large object files
- Lambda: Run small bits of code (several languages) in response to AWS events
- Athena: SQL on S3 data files (structure JSON, CSV...)
- Comprehend: NLP
- Lex: Chatbox, Alexa integration   


## Data visualization, infographics and reporting

- [D3.js](https://d3js.org/)

![](https://d3js.org/preview.png)

- [Jupyter](https://jupyter.org/)

![](https://cdn-images-1.medium.com/max/1000/1*mTfjnFoMMq8kgUUA_28LiQ.jpeg)

