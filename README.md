# BigdataProject

**Group members :**
- Sai Kumar Murugavel (1210580)
- Kaarthik Sekar (1218831)
- Dishant Bhattacharya (1217597)
- Ayush Sharma (1218850)

### Project Name - **Airtime Calculation using Regression Models in pyspark**

### Algorithms used 
1. Linear Regression
2. Multilinear Regression
3. Random Forest Regression

### 1. Installation Steps 
1. Simply clone the repository 
2. In the repo navigate to the code folder, and run the ipynb file.
3. Use the command ` Spark-submit “pathname” `

### 2. Cluster Information 
1. Create the master cluster using the `spark-class org.apache.spark.deploy.master.Master`
<img width="682" alt="Screenshot 2023-11-30 at 9 56 16 PM" src="https://github.com/Vig-T/BigdataProject/assets/51297736/bd234bc4-b93e-43e9-bde8-ccf5ee468193">

2. Create the worker cluster and connect it with the master cluster `spark-class org.apache.spark.deploy.worker.Worker spark://10.0.0.219:7077`
   
![image](https://github.com/Vig-T/BigdataProject/assets/51297736/42c53f1a-f47d-414c-8ada-1649aecaf17d)

4. Check the information about the worker & master in the spark dashboard
<img width="1436" alt="Screenshot 2023-11-30 at 9 59 09 PM" src="https://github.com/Vig-T/BigdataProject/assets/51297736/89502027-a6f2-4a0f-b44f-a03186eff51d">

### 3. Output 
- Navigate to Anaconda navigator and run the jupyter notebook, navigate to your folder with 'code' and run it in the jupyter notebook. Each file has its own **ML algorithms** which are being used to calculate the airtime of the flight.
<img width="1436" alt="Screenshot 2023-11-30 at 10 06 44 PM" src="https://github.com/Vig-T/BigdataProject/assets/51297736/cb9b8884-3883-498b-a064-894585bc6f9d">

### 4. Environment 
- Hadoop 3.3
- Spark 3.5
- Anaconda Jupyter Notebook


