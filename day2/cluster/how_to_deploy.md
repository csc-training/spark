#### How to deploy the spark cluster

1. Navigate to rahti.csc.fi
2. Click on Rahti Web User Interface
3. Login using your customer accounts or training accounts
4. On the dashboard click on Apache Spark
5. In **Add To Project** -> Click on **Create Project**
6. Enter the project name, *preferably your own name/username there*
7. Enter the **Cluster name**, *again preferably your own name/username*
8. Create a new **Username** and **Password** for logging into spark and jupyter **(Do not use existing usernames and passwords, create new ones for demo purposes!)**
9. Change the number of **Worker Replicas** to 2
10. Change the **Storage Size** to 15Gi
11. **Most importantly : Do not click Next, wait for further instructions**



### Once the cluster has been deployed

1. Open the jupyter and spark links (Instructions will be given)
2. Login using the usernames and passwords you just created above
3. Open a new terminal in jupyter and run the following commands:
  - cd /mnt/<Cluster_Name>-pvc/
  - wget https://spark-course.object.pouta.csc.fi/reviews_Books_5.json
  - wget https://spark-course.object.pouta.csc.fi/Cluster.ipynb
4. Wait for further instructions
