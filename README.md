# sinch-challenges

## Challenge proposed by Sinch to answer business questions regarding a chatbot service.

1. To check the solution just run the jupyter notebook in Google Colab:
   ```
   https://colab.research.google.com/drive/1M0E8ITA8xsX8wmu-b4rm07fc31jiiYAG?usp=sharing
   ```  

2. Thinking about simplicity, speed of execution, cost and scalability, an architecture was proposed to run the developed notebook and make the data available in the cloud in an easy and transparent way. 

    Spark was used to process the data, which would be an overkill for the available sample size, but would be a great choice when the data volume started to grow. And to run this notebook, Dataproc was thought of, a serverless service that can run Spark Notebooks and destroy the Infrastructure, without having to manage or continue using something for a specific purpose. 

    The data would then be made available in BigQuery tables to be consumed by the team and interested people. In the bigquery itself we could configure access to the data, in which we can reach the granularity of the line, giving access only to authorized people. To check the diagram, acess it (or just open [sinch.png](https://github.com/iuriqc/sinch-challenges/blob/main/sinch.png) in this repository):
    ```
    https://drive.google.com/file/d/1wkuayFSxIUa6md1edIaEv4v9k__is8wo/view?usp=sharing
    ```
