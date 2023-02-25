# Gitpod workspace for Apache Superset (samples included)

Gitpod workspace definition for experimenting with Apache Superset - the open source data exploration and visualization platform

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/lucasjellema/gitpod-apache-superset)

Once the workspace is up and running, the following components will have been installed:
* Apache Superset
* PostgreSQL 
* Redis

all running in a Docker Container. This picture shows the contents of the workspace:
![](images/workspace-architecture.png)  

To get going, you can read through [this article](https://technology.amis.nl/data-analytics/getting-started-working-with-apache-superset-the-open-source-data-exploration-and-visualization-platform/) that introduces Apache Superset and the workspace. Some quick instructions:


Open port 8088 to enter the Superset web UI. Login with user admin and password admin.

![](images/open-port-and-login.png)  

You will enter the main page where you can start adding database connections, datasets, charts:

![](images/main-dashboard.png)  
A Postgres database, named examples, is included and pre-configured in Superset for you. 
![](images/examples-db.png)  

Quite a few data sets – derived from this examples database – are predefined in the workspace environment:

![](images/datasets.png)  

To quickly create a Visualization for one of these datasets, start the Explore workflow from the Datasets tab, start by clicking the name of the dataset that will be powering your chart: cleaned_sales_data: 

This is the no code, drag & drop visualization editor that you will see: 

![](images/viz-editor.png)  

By clicking, dragging and dropping the data set fields the following stacked bar chart visualization is quickly composed:

![](images/stacked-xchart.png)  

Click on the link View all charts to select the desired chart type:

