[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/foXtNvtG)


# README

- [Structure of the repository](#Structure-of-the-repository)
- [Main goal of the project](#Main-goal-of-the-project)

## Structure of the repository

In this project I wanted to solve the Travelling Salesperson Problem using Python. A brief literary review/introduction for the theoretical background can be found in the [TSP_review.pdf](TSP_review.pdf) file. The code is uploaded in pdf format [TSP.pdf](TSP.pdf) and as a jupyter notebook [TSP.ipynb](TSP.ipynb) which users can download and run.

Before running the code make sure that all the important modules are installed on your device.
- numpy
- random
- math
- pandas
- copy
- matplotlib
- ipywidgets

Usually when you download python these packages are downloaded as default, so probably you wont't need to perform any special tasks before running the code. The data is generated, all workings are available in the notebook [TSP.ipynb](TSP.ipynb).

## Main goal of the project

During the implementation of the project, the main focus was on Simulated Annealing, but I also implemented the Ant Colony Optimization method (based on different sources as referenced in the notebook) and compared their performances. I created supplementary diagrams for both models for a deeper understanding of the problem. The analysis of the results will be available during the presentation at the end of the year. Since the hyperparameter tuning can take a lot of time I decided to create interactive plots such that the users can play with the them. This way the users can get an impression how the hyperparameters are influanceing the results.

As a final result I found that both methods are appropriate for this problem, the Simulated Anneling might be a bit more robust to different choice of hyperparameters.



