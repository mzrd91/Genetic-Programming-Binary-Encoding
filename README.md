# Genetic-Algorithm-Binary-Encoding

This project builds on the problem solved in Project #1, implementing binary (bit-string) encoding for the solution. The main objective is to use binary encoding for variables $x1$, $x2$, and $x3$, and to evaluate the algorithm's performance across multiple runs.

## Purpose

The purpose of this project is to apply genetic algorithms using binary (bit-string) encoding to optimize a mathematical function. Through this project, you will learn to implement and tune Genetic Algorithms(GA), represent continuous variables as binary bit-strings, and perform statistical analysis on the algorithm's performance. The project aims to enhance your understanding of **Genetic Algorithms**, improve problem-solving skills, and provide practical experience in **optimization techniques**.


## Features

- **Binary Encoding:** 
  - 15 bits for x1
  - 20 bits for x2
  - 25 bits for x3

- **Algorithm Parameters:**
  - Population size, crossover rate, mutation rate, etc., can be specified by the user via the command line, provided at the beginning of execution.

- **Output Metrics:**
  - Best, mean, and standard deviation of the best-of-run fitnesses from 30 independent runs.
  - Details of the best solution from these runs, including:
    - Bit-string representation
    - Corresponding floating-point values for x1, x2, and x3
    - Fitness value

## How to Run

1. **Setup:**
   - Clone the repository
   - Ensure you have Python installed along with the necessary dependencies

## Code Implemenation:
Run [GA-Binary-Encoding.ipynb](GA-Binary-Encoding.ipynb)

![image](https://github.com/mzrd91/Genetic-Programming-Binary-Encoding/assets/131927177/65dcca90-6194-4540-b9e8-c460291d92d7)


3. **Output:**
   - The program will output the best, mean, and standard deviation of the best-of-run fitnesses from 30 independent runs.
   - The best solution's bit-string representation, the floating-point values of $x1$, $x2$, and $x3$, and the fitness value will be displayed.
  
## Example Output

The output of the algorithm after running 30 independent runs is as follows:

- **Average Best Fitness:** 22.2357
- **Standard Deviation of Best Fitness:** 13.3645

### Best-of-Run Solution:

- **Bit-string Representation:** `111100110111110010010001100010010010010001011101110100011110`
- **Floating-point Values:** 
  - $x1$ = 3.4625
  - $x2$ = -3.8733
  - $x3$ = -5.4990
- **Fitness Value:** 0.0427

### Explanation of the Output:

- **Average Best Fitness:** This is the average fitness value of the best solutions found in each of the 30 independent runs of the genetic algorithm.
- **Standard Deviation of Best Fitness:** This measures the variability of the best fitness values across the 30 runs.
- **Bit-string Representation:** This is the binary encoding of the best solution found during the runs.
- **Floating-point Values:** These are the decoded real values corresponding to the bit-string for variables $x1$, $x2$, and $x3$.
- **Fitness Value:** This is the fitness value of the best solution, indicating how well this solution optimizes the objective function.


## Visualization
This plot shows the best fitness value in each generation for all 30 runs. The black line represents the average best fitness value across all runs per generation. This visualization helps in understanding how quickly the algorithm converges and how the fitness values improve over generations.

[Fitness Progression Over Generations](images/image.png)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or issues, please contact me at [m.zrd91@gmail.com].
