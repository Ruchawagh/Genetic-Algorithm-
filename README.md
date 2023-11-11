
# Genetic-Algorithm Travelling SalesMan Problem
To fine the least cost route of set of n cities so that each city visits exactly once
# STEPS TO EXCEUTE ALGORITHM


1)Initialize the paramaters like Population, No of city , Tour size.


2)Generate the first population (random  values to generate  chromosomes which appends to population size.


3) Method to verify if the number is already in the path


4)Generates the X and Y arrays which represents the distances in the x and y axis used to calculate the identity matrix(dicadade) in the fitness function.


5)makes the swap between 2 cities in the path with a 5% chance of mutation.


6) Generates the Tour matrix, which is the same matrix as the population,but with the first column duplicated at the end of it, afterall, the travelleralways have to arrive at the same place of where he started.


7) Generates an array with the sum of each path in the population array  based on the tour matrix.


8) Generate the identity matrix (dCidade) based on the x and y arrays and then call the calculateDistances() method to generate the array with the sum of each path to user later in the cycle process.


9)Performs the roulette function, generating two arrays with 5 parents each, which will be used later to do the cycle process



10)Method used in the cycle method to see if there's any duplicated city.


11)Method that has the 'cycle' logic.
    -For each two children in the children array, makes a random swap between
        the two children until there's no duplicated element
    - Mutate the children that were generated
    -Adds the children in the population array




12) Generates the fitness values for the last population
   2)Show th path graph
   3)show the fitness value over the no of iterations.

    

<img width="524" alt="output" src="https://github.com/Ruchawagh/Genetic-Algorithm-/assets/99780429/a0e02027-e6a2-4fbf-aae2-88f9694deeeb">

![graph 1](https://github.com/Ruchawagh/Genetic-Algorithm-/assets/99780429/e0c718be-d894-4853-945c-1b46cd035331)

![graph 2](https://github.com/Ruchawagh/Genetic-Algorithm-/assets/99780429/305b50fd-603e-4f2c-b8b0-e700a59da263)


