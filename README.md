# GraphX for Airports and Tweet Processing & Classification using Pipelines

## Overview
This project involves two tasks:
1. GraphFrame for Airports: Analyzing a dataset representing connections between various airports using GraphFrame.
2. Tweet Processing & Classification using Pipelines: Classifying tweets about US airlines as positive, neutral, or negative using logistic regression classifier and pipelines for pre-processing and model building.

## Installation of GraphFrame
To use GraphFrame in Databricks, you need to install the graphframes package. Here's how you can do it:
1. Go to your Databricks, click on the "Clusters" tab in the sidebar.
2. Create a cluster using Databricks Runtime ML: When you create a cluster, select a Databricks Runtime ML version from the Databricks runtime version drop-down menu. Both CPU and GPU-enabled ML runtimes are available.
3. Click on "Libraries" and then "Install New".
5. In the "Library Source" dropdown, select "Maven Coordinate".
6. In the "Coordinate" field, enter "graphframes:graphframes:0.8.1-spark3.0-s_2.12".
7. Click "Install" to install the GraphFrames package.

## Running Cells in Databricks
To run cells in Databricks:
1. Click on a cell to select it.
2. Press `Shift` + `Enter` to run the selected cell.
3. Alternatively, you can click on the "Run" button at the top of the notebook to run all cells in the notebook.

## Check the Analysis Here
1. [GraphFrame for Airports](./Part I.ipynb)
2. [Tweet Processing & Classification](./Part II.ipynb)
