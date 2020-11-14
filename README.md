# Predicting Bike Sharing Patterns

This repository represents a solution to the first project of Udacity's Deep Learning nanodegree.


## Overview

A bike sharing system is a service in which bicycles are made available for shared use to individuals on a
short term basis for a price or free. The goal of this project was to build a neural network model that predicts the number
of borrowed bicycles in a specific day to better help bike sharing associations understand their customers' behavior and improve
their business according to it. To carry out the problem, the model was built on a real dataset which you
can find [here](https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset).
<br/><br/>

## Understanding the Dataset

This dataset has the number of riders for each hour of each day from January 1 2011 to December 31 2012. The number
of riders is split between casual and registered, summed up in the `cnt` column. You can see the first few rows
of the data and a visualization of the first 10 days below.
<br/><br/>
<p align="center">
<img src="Images/dataset.png" alt="dataset image" width="800" />
</p>

<p align="center">
<img src="Images/10days.png" alt="10 days visualization" width="450" />
</p>

## Understanding the Model
Splitting the dataset's attributes into features and target was the first step of building the nueral network. The figure below takes the features as inputs, and predicts and `cnt` as output.
<br/><br/>
<p align="center">
<img src="Images/neural_network.png" alt="nueral network" width="350" />
</p>

## Get Started
1. For best experience with managing dependencies, install [Anaconda](https://docs.anaconda.com/anaconda/install/) or
[miniconda](https://docs.conda.io/projects/continuumio-conda/en/latest/user-guide/install/macos.html)


2. Create a new environment
```
conda create --name deep-learning python=3
```
3. Enter the environment
* for Mac/Linux `>> source activate deep-learning`
* for Windows `>> activate deep-learning`

4. Install the dependencies
```
conda install numpy matplotlib pandas jupyter notebook
```
5. Clone or download the zip file of the repository
```
git clone https://github.com/OrjwanZaafarani/Predicting_Bike_Sharing_Patterns.git
```
6. Navigate to the repositry's location on your device
```
cd the_path_where_you_saved_the_repository/Predicting_Bike_Sharing_Patterns
```
7. Launch a jupyter notebook server
```
jupyter notebook
```
8. Your browser will open the server's window. Access Predicting_bike_sharing_data.ipynb


9. Run the notebook all at once by clicking the Run button or run it cell by cell using `Shift+Enter`
<br/><br/>
## What to Expect
If everything runs correctly, the model should ouput the following
<br/><br/>
<p align="center">
<img src="Images/output.png" alt="output image" width="500" />
</p>
