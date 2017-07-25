# Traveling Salesman Genetic

This Project Solves the Traveling Sales Person Problem using genetic algorithm with the following properties:
* Chromosomes decoded as cycles (solutions) of traveling
* Order 1 crossover
* Swap mutation
* Complete generation replacement
* Roulette Wheel Technique for choosing parents
* Negative of cycle distance as fitness

Documentation
-------------
The code is documented using Google Style Docstring but for a detailed documentation read the  [documentation.md](https://github.com/AminFadaee/Traveling_Sales_Man_Genetic/blob/master/documentation.md)

Requirements
--------

* Python Version 3+
* numpy
* matplotlib

Running:
---
Run the project by running TSPG.py

Here is the results for [input1.txt](https://github.com/AminFadaee/Traveling_Sales_Man_Genetic/blob/master/input1.txt) :

![some](https://github.com/AminFadaee/Traveling_Sales_Man_Genetic/blob/master/figure1.png)

and [input2.txt](https://github.com/AminFadaee/Traveling_Sales_Man_Genetic/blob/master/input2.txt) :

![some](https://github.com/AminFadaee/Traveling_Sales_Man_Genetic/blob/master/figure2.png)

Both runs use the following parameters:

* n = 20
* k = 100
* max_generation = 1000
* crossover_probability = 0.99
* mutation_probability = 0.01

License
-------

The MIT License. Copyright (c) 2017 Amin Fadaee

About Author
----------------

[Amin Fadaee](https://www.linkedin.com/in/aminfadaee/)
