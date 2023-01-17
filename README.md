# AutoEDA-Autoviz-EDA-Library

-----------------------------------------------------------------------------------------

* EDA (Exploratory Data Analysis) is an approach to understanding the data before modeling. Before predicting or modeling, one should explore the data to get insights about what the data is exactly all about. Visualization is the key component of EDA which can be defined as a graphical representation of the data in a pictorial or graphical format using graphs, charts, maps, etc to identify patterns and trends in the dataset. Through visualization, it becomes easier to understand the dataset and helps in decision-making. There are many different libraries in python that are used to make visualizations like Matplotlib, Seaborn, Plotly, ggplot, Geoplotlib, Gleam, etc. But while using these, there is a need to define the type of graphs we want and pass various parameters. Therefore,we have a very interesting library in python named "Autoviz" which is an automated visualization library.

-----------------------------------------------------------------------------------------

What is Autoviz?

Autoviz is an open-source python library that identifies key features in a dataset and automatically generates some basic and beautiful visualizations with just one line of code.


It is maintained by the package https://github.com/AutoViML which has many such libraries that provide automated results with just one line of code which makes data scientists' work easier and more productive.

-----------------------------------------------------------------------------------------
Its Key Features:

1) It identifies the key features in a dataset and generates the most impactful visualization
2) It just takes 3-4 seconds to generate the visualizations.
3) It works well with any size of data.
4) All the magic happens with just one line of code.

-----------------------------------------------------------------------------------------
How to install it?
```
pip install autoviz
```

-----------------------------------------------------------------------------------------
How to import it?
```
from autoviz.Autoviz_Class import Autoviz_Class
```
-----------------------------------------------------------------------------------------
How to initiate it?
```
AV = AutoViz_Class()
```
```
AV.AutoViz(‘dataset_name’)
```
-----------------------------------------------------------------------------------------
AND WE'RE DONE!

Official Site:

https://pypi.org/project/autoviz/0.0.6/
