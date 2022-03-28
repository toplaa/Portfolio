
## [Project 1- Machine-learning - Decision tree](https://github.com/toplaa/Machine-Learning-Projects/blob/main/Decision%20Tree.ipynb)
In this project, I built a classification algorithm to build a model from historical data of patients and their responses to different medication. Then used the trained decision tree to predict the calss of an unknown patient to find proper drug

To See other Machine Learning Algorithms Such as KNN, Regression, Clustering etc.., Click ---> [HERE](https://github.com/toplaa/Machine-Learning-Projects)

![](/images/DT.png)

## [Project 2- Data-Engineering-Project.-Postgres-Data-Modeling ](https://github.com/toplaa/Data-Engineering-Project.-Postgres-Data-Modeling)
This project is one of the projects that I did from Udacity Nanodegree.

The purpose of this database is to be able to extract, transform and load different json files that are located in different paths. For this project, there are some variables (columns headers )that are in different paths(song_data and log_data), in addition, there is some other information such as the log information that are also in a different path. With a careful study of the table, one was able to identify fact tables and dimension tables that are referenced in order to develop a logical schema. With the ETL , we are able to create relevant tables with the required information and apply the appropriate SELECT statement to transform some of the data. The table is now a more organised version of the data instead of the different json files that are in different paths, as such the analytical teams can perform further analysis and transformation on the data to meet their different goals.

The database schema here is the STAR -Schema for the following reasons: It is simple and most widely used in the industry It contains one fact table and some other dimension tables that can reference each other It also simplifies the queries and minimizes the number of JOINS

The link to the repository can be found [HERE](https://github.com/toplaa/Data-Engineering-Project.-Postgres-Data-Modeling) 

The descriptions of the files in the repository are as follows:

test.ipynb --> displays the first few rows of each table to let you check your database.

create_tables.py --> drops and creates your tables. You run this file to reset your tables before each time you run your ETL scripts.

etl.ipynb --> reads and processes a single file from song_data and log_data and loads the data into your tables. This notebook contains detailed instructions on the ETL process for each of the tables.

etl.py --> reads and processes files from song_data and log_data and loads them into your tables. You can fill this out based on your work in the ETL notebook.

sql_queries.py ---> contains all your sql queries, and is imported into the last three files above.

README.md --> provides discussion on your project.

## [Project 3- Data-Engineering-Project.-Data Lake Project (Local Machine and On Cloud (AWS) ](https://github.com/toplaa/Data_Lake-Project_Udacity-)
This project is one of the projects that I did from Udacity Nanodegree

The purpose of this database is to be able to extract, transform and load different json files that are located in different paths. For this project, there are some variables (columns headers )that are in different paths(song_data and log_data), in addition, there is some other information such as the log information that are also in a different path. With a careful study of the table, one was able to identify fact tables and dimension tables that are referenced in order to develop a logical schema. With the ETL , I was able to create relevant tables with the required information and apply the appropriate SELECT statement to transform some of the data. The table is now a more organised version of the data instead of the different json files that are in different paths, as such the analytical teams can perform further analysis and transformation on the data to meet their different goals.

For this particular project, the input data is transformed from AWS s3 bucket, and after the transfromation is completed, the output data is loaded back to s3. It should be noted that this process can also be performed locally.

The database schema here is the STAR -Schema for the following reasons: It is simple and most widely used in the industry It contains one fact table and some other dimension tables that can reference each other

Please Note: I ran this project locally on my personal machine

The link to the repository can be found [HERE](https://github.com/toplaa/Data_Lake-Project_Udacity-) 


## [Project 4- Publication from my PhD- Textural and Mineralogical Controls on Rock Strength Elucidated Using a Discrete Element Method Numerical Laboratory](https://www.mdpi.com/2075-163X/11/9/1015)

Numerical modelling techniques such as the discrete element method are now well established and extensively used in many applications including solid earth geoscience, materials science, geotechnical engineering and rock mechanics. The potential for this technique in understanding comminution mechanisms has been identified as highly promising. This work utilizes the discrete element method as a numerical laboratory to conduct investigations relevant to comminution that would otherwise be costly or time-consuming to perform in the field or laboratory. A benchmark numerical model for impact breakage of rock specimens is first established and validated against results of controlled laboratory experiments. Thereafter, the model is utilized to systematically investigate the potential dependency of ore breakage properties upon the prevalence of pre-existing fractures, as well as the mineralogical composition of the ore. These numerical experiments serve to highlight the potential for quantitatively relating the mechanical response of ore to its textural and mineralogical characteristics. Tandem utilization of numerical and laboratory experimentation to formulate and test hypotheses is a promising avenue to illuminate such relationships.

To Read Full Article, Click---> [Here](https://www.mdpi.com/2075-163X/11/9/1015)

![](/images/predict2.png)
![](/images/predict.png)


