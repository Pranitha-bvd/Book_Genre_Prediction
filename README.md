# Setting Up Databricks Environment for Book Genre Prediction Model
To open and run the "Book Genre Prediction.dbc" file in Databricks Community Edition, please follow these steps. If you encounter any issues, feel free to contact me for assistance.

## Importing the File:

Navigate to the Databricks Community Edition and click on the workspace panel on the left side. Import the "Book Genre Prediction.dbc" file into your workspace. Creating a Cluster:

Go to the 'Compute' tab in the Databricks menu. Click on 'Create Cluster', which you can find on the left side of the screen. Provide a suitable name for your cluster. For the 'Runtime Version', select '12.2 LTS ML', which includes Apache Spark 3.3.2 and Scala 2.12. Installing Required Libraries:

Once the cluster is created, click on it and navigate to the 'Libraries' tab. To install the necessary libraries for running the model, click on 'Install New'. Choose 'PyPI', then enter the package name "spark-nlp==5.1.4" and click 'Install'. Again, click on 'Install New'. This time, select 'Maven'. Under 'Search Packages', choose 'Maven Central' from the dropdown menu. In the query tab, search for "spark-nlp_2.12". Select the package "com.johnsnowlabs.nlp:spark-nlp_2.12:5.1.4" and install it. The installation of these packages may take a few minutes. Running the Code:

After the libraries are successfully installed, your cluster is ready to run the Spark NLP code. These steps will guide you through setting up your Databricks environment to run the Book Genre Prediction model. The notebook is designed to be self-explanatory, guiding you through each process step-by-step.
