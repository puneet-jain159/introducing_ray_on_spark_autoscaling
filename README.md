# Announcing Ray Autoscaling support on Databricks and Apache Spark
This Repository contains the notebook published in the blog Announcing Ray Autoscaling support on Databricks and Apache Spark

With the release of **Ray 2.8.0**, we have enabled Ray auto-scaling with Ray on Databricks and Apache Spark. Below, we showcase the functionality by going through an example of hyper-parameter tuning for a deep learning model on the CIFAR dataset.

Ray Auto-scaling works with **DBR runtime 14+**, and the code has been tested with the following cluster configurations:

**Azure**: Driver NC6s_v3 and autoscaling with 4 worker nodes NC6s_v3.
