# TIBCO-HACKATHON-SUBMISSION

Instructions to RUN :

To run the system , kindly follow the following steps :

Step 1 : Unzip the zip file , you will find the KNN.java file and a file named "File3" which contains sample values. The demo video is also shared which clearly explains the process and configuration details for configuring endpoints, pipelines and database.

Step 2 : In your Project Air Implementation create and deploy 2 pipelines.  Firstly configure the communication endpoints (The EggexMQTT and AirMqtt ) with details as per the documentation.

Step 3 : Deploy the first Pipeline containing a data subscriber and data publisher to to simulate the "water conductance" data coming to the Rest Device Screen.

Step 4: Depoly second pipeline containing a data subscriber and Data Store . This will enable sending the data ("conductance value for water") to the postgreSQl.

Step 5: In the KNN.java program match the file location to the location of the file3 in the zip file as per your file location.

Step 6 ; Run the KNN.java program in any IDE , this will give the output , if the water is "Safe or Unsafe" for usage.
