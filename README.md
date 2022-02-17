# Sales_Analysis_Report

## Setup

### To access all of the files I recommend you fork this repo and then clone it locally.
Instructions on how to do this can be found here:  
https://docs.github.com/en/get-started/quickstart/fork-a-repo
<br />
<br />
The other option is to click the green "clone or download" button and then click "Download ZIP". You then should extract all of the files to the location you want to edit your code.
<br />
<br />
Installing Jupyter Notebook: https://docs.jupyter.org/en/latest/install.html  
Installing Pandas library: https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html  

## Background Information:
 
In this repo I used Python Pandas & Python Mathplotlib to analyse and answer business questions about 12 months worth of Sales data. The data contains hundreds of thousands of electronics store purchases broken down by month, produuct type, cost, purchase address, etc.
<br />
<br />

We start by cleaning our data. Tasks during this section include:
* Drop NaN values from Dataframe.
* Removing rows based on a collection.
* Change the type of columns(to_numeric, to_datetime, astype)
  
  
Once we have cleaned up our data a bit, we move the data exploration section. In this section we explore 5 high level business questions related to our data:
  
  
* What was the best month for sales? How much was earned that month?
* What city sold the most product?
* What time should we display advertisemens to maximize the likelihood of customer’s buying product?
* What products are most often sold together?
* What product sold the most? Why do you think it sold the most?
  
  
To answer these questions we walk through many different pandas & matplotlib methods.  They include:
  
  
* Concatenating multiple csvs together to create a new DataFrame (pd.concat)
* Adding Columns
* Using the .apply() method
* Using groupby to perform aggregate analysis
* Plotting bar charts and lines graphs to visualize our results
* Labelling our graphs
