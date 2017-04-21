# Visualizing Earthquakes in Relation to Global Temperature

The interactive visualization compares the development of the number of earthquakes per year or per month with the development of the global temperature. It is realized in two different ways, one using JavaScript and D3.js and the other one using Python and Bokeh.  

Directly go to:
[D3.js](https://github.com/JonathanAsamoah/Portfolio/tree/master/Visualizing%20Earthquakes%20in%20Relation%20to%20Global%20Temperature/JS_D3.js)
[Bokeh](https://github.com/JonathanAsamoah/Portfolio/tree/master/Visualizing%20Earthquakes%20in%20Relation%20to%20Global%20Temperature/Python_Bokeh)
[Data Preprocessing](https://github.com/JonathanAsamoah/Portfolio/tree/master/Visualizing%20Earthquakes%20in%20Relation%20to%20Global%20Temperature/Python_Preprocessing)

# Languages/Technologies

* Python 
  * pandas
  * Bokeh
 * JS
  * D3.js
* Visualizing Data

# Remarks

The visualization in this projects is made with two different approaches. In the first one plain JavaScript and D3.js is used. In this project the data the visualization is build on is included in the data folder in repository. 

The original data is not included in the repository. To download the data to the repository run the *Download the data* section in the preprocessing file once. After that the lines which call the download function can be comment out to prevent the code from downloading the data every time you run the code.

Also, there is an additional preprocessing file that generates the data file that is used for the visualization from the orginal data files.

The python projects contain a requirements.txt file. Which you can use to load the required libraries for the project using ``pip install -r requirements.txt``.

# Data

* [Kaggle: Significant Earthquakes](https://www.kaggle.com/usgs/earthquake-database)
* [dataokfn: Global Temperature](http://data.okfn.org/data/core/global-temp)
