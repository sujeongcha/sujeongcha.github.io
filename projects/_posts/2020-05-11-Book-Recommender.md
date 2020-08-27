---
layout: post
title: Building Scalable Book Recommender Systems
---

![placeholder](https://sujeongcha.github.io/public/bookRecommend.jpg "Photo by Christin Hume on Unsplash")

<div class="message">
  <ul>
    <li> Task: Recommender Systems based on Machine Learning </li>
    <li> Models: Alternating Least Squares with NMSLIB HNSW indexing for fast search
    <li> Language: PySpark (on Apache Spark) </li> 
  </ul>
</div>

#### Recommender needs big, big, big data...

This project aims to build a book recommender system using Apache Spark’s machine learning library, MLlib. Python, a traditional but popular tool, offers easy-to-use machine learning packages, but they are deployed on a single machine and consequently restricted in terms of scalability. On the other hand, Spark takes advantage of parallelism and can speed up ML performance on “Big Data”. Hence, Spark MLlib is an appropriate choice for our book interactions dataset considering its size (4.32 GB in CSV).

However, we could not utilize the full dataset as the job was aborted on NYU's Hadoop cluster (Dumbo) due to OutofMemoryError. Hence, the precision results may not be satisfactory, but it was still a good starting point for implementing machine learning models on a large-scale basis.

Final report and PySpark scripts can be found <a href="https://github.com/sujeongcha/team-deep-coral">HERE</a>.
