# Costco Sales-Forecasting

The project is implemented in Python.

The project will run in Google colab. 

# Setting up project in google colab

The data can be uploaded using the upload button present in the left page menu navigator.

If you are uploading the path to import file in the first code block need to be of format.

`./MSK_WHS1_FY19_P3.csv`

Cons of uploading the file is whenever you restart the colab you have to reupload.  
Hence, better way is click on Mount -> it will create a new code block -> run it -> click on link to give permission to your drive -> authorize and copy api token -> paste it back in the code block and hit enter. Voila! your drive is mounted. 

Please note you have to mount your drive whenver you restart google colab. 

Now, please upload the data into your drive.

To access data in code now you have to edit the first code block where we are importing data into format,

`/content/drive/My Drive/{folder you have created in your drive and path to files}`

Ex: If I upload the data into dataMining folder in my drive the path will be

`/content/drive/My Drive/dataMining/MSK_WHS1_FY19_P3.csv`

Now that we have uploaded the required data.  

Google colab must run without any exceptions. 
If any packages are not found or if any new needs to be installed,  
The packages required in Google colab can be installed using 
```
!pip install apyori
```
type this in any code block and execute. 

# Data exploration and analysis

The file DM-project-TableauVisualization is be accessed via tableau, you need to have latest Tableau-2020.1.2 version to run

# Code 
The main notebooks that are there in the code are 
1) Association rules.ipynb
2) Forecasting-Arima/Arima.ipynb
3) Forecasting-LSTM/Sales Forecasting .ipynb
