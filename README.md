[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/foXtNvtG)


# README


## Structure of the repository

In this project I wanted to solve the Travelling Salesperson Problem. A brief literary review/introduction for the theoretical background can be found in the [TSP_review.pdf](TSP_review.pdf) file. The code is uploaded in pdf format [TSP.pdf](TSP.pdf) and as a jupyter notebook [TSP.ipynb](TSP.ipynb) which users can download and run. The presentation is available under the file [TSP_presentation.pdf](TSP_presentation.pdf).

## Before you start

In this project I used Python, so if you want to run the code it's necessary to download it. I recommend to download Python with Anaconda, a detailed guide for this is available [here](https://docs.anaconda.com/free/anaconda/install/).

All the modules I useD in the project are automatically installed during the anaconda installation, so


Before running the code make sure that all the important modules are installed on your device:
- numpy
- random
- math
- pandas
- copy
- matplotlib
- ipywidgets

If you are using Anaconda, all the modules I've used in the project are installed as default during the anaconda installation, so you won't have any further things to do.


## Main goal of the project and relevance

The Travelling Salesperson problem is a well known problem in computational science, it has many applications in logistics, but it also appeares in seemingly remote areas such as DNA folding. The main goal of the project was solving the Travellig Salesperson problem with Simulated Annealing but I also implemented the Ant Colony Optimization method (based on different sources as referenced in the jupiter notebook). At the end of the project I also compared their performances.

I used simulated data for this project, and I tried to create supplementary diagrams for both models for a profound understanding of the problem. A deeper analysis of the results will be presented at the end of the year.

## How to run the code

### Simulated Annealing

After running the code, users only need to call the function `SA()` to do Simulated Annealing. It will generate a (pseudo) random configartion of cities and will find a (sub) optimal route on the configuration. 

The function has the following inputs:

- `N`: integer (default is 20). It controls the number of cities to visit. 
- `T_0`: integer (default is 1000). It controls the initial temperature of the simulated annealing
- `alpha`: float (default is 0.99). It's the cooling hyperparameter.
- `width`: integer (default is 10). It controls the width of the map.
- `height`: integer (default is 10). It controls the height of the map.
- `seed`: integer (default is None). You can set a seed and generate the same configuration of cities.

The function has the following outputs:

- `initial_r`: it stores an intial guess for the route
- `best_r`: it stores the current best route
- `Ts`: it stores the temperatures during the cooling process
- `ps`: it stores the acceptance probabilites
- `total_dist`: it stores the total distance travelled at a ceratin route

For example running the following code will produce the following plot:

`initial_r, best_r, Ts, ps, total_dist = SA(seed=42)`

`initial_r.plot_route()`

`best_r.plot_route()`

![SA_init](https://github.com/ACM40960/project-fischu42/assets/115270211/c193ed87-d7f8-4b8f-8400-476ecf53bf05)
![SA_sol](https://github.com/ACM40960/project-fischu42/assets/115270211/16e85d6c-65db-4047-9a46-da6d746fe2c3)




### Ant Colony Optimization

### Hyperparameter Tuning








