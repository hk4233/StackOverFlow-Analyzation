# StackOverFlow-Analyzation

Required software:

-> Jupyter notebook or google colab

-> MySQL Workbench


# Sample Data:

Sample data is given as a csv file with 500 instances such that it satisfies different scenarios
and represents the main table in our database structure.


#Setup:

Download and setup MySQL Workbench (reference link is https://dev.mysql.com/doc/workbench/en/wb-installing.html)

Create a new connection with Connection name - stackoverflow

Username - root

Password - rootroot


# Data Management (DataManagement folder):

Open the Script.ipynb file using Jupiter notebooks or google colab.

Copy the actual path of Sample_Questions.csv file present in Sample Data folder and paste it 

in line 2 of cell 1 where it says 'File path here'

Now run the file in Jupyter notebook by selecting Cell -> Run All or  
in google colab by selecting Runtime -> Run All
This inserts the data into MySql Workbench, it should be quick as it has only 500 instances.

More details on data loading and time taken can be found in the project report, Design and Implementation Section.


# Data Analytics (DataAnalytics folder):

Simply open the Analyses.ipynb file either using Jupyter notebook or google colab and run using Run All option as described in Data Management section. This file contains all the visualizations for different analyses performed on the stack overflow dataset to observe trends and patterns.

Open the Model.ipynb file either using Jupyter notebook or google colab and run using Run All option as described in Data Management section. This file contains the Gradient Boosting Model which takes the input data which is processed using natural language processing. 

In detail description of above files can be found in the project report, Analyses, and Design and implementation sections.

