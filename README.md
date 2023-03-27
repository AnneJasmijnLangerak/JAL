# JAL

Code belonging to "JAL: a JSON algebra for the optimization of JSON queries".

All software is written in the programming language Python3 (https://www.python.org/) via JupyterLab/ JupyterNotebook (https://jupyter.org). For the parsing of JSONiq queries, we used the JSON engine Rumble that runs on top of Apache Spark (https://www.rumbledb.org).

## Repository content
There are two folders contained in this repository:

1. Data: containing all the collections used for the queries
2. Notebook: containing the Jupyter Notebook with all the code

## Installation instructions
1. Download Anaconda Navigator: https://www.anaconda.com/products/individual
2. Download Rumble: https://github.com/RumbleDB/rumble/releases/download/v1.6.3/spark-rumble-1.6.3.jar
3. Download this repository by pressing on the green button above 

## Run code

1. You can either open the repository in JupyterLab or in JupyterNotebook
2. It is possible to run the entire notebook at once (although not recommended), or run each cell separately by continously pressing on the run button at the top. Note that you need to run all the cells (containing functions) in order to run the queries

## Query parsing
To check if the syntax of the JSONiq is correct, each query is tested on empty collections in seperate rumble cells. These cells can be recognized as they start with %%rumble. If the output of such a cell is the empty [], the syntax of the query is correct.

## Data sources

- https://github.com/jdorfman/awesome-json-datasets
- https://data.world/city-of-tempe/40b49ebc-ff11-43ed-b814-b5137fc53b4c/workspace/project-summary?agentid=city-of-tempe&datasetid=40b49ebc-ff11-43ed-b814-b5137fc53b4c
