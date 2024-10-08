# Knapsack Problem Solver with Dynamic Programming

## Project Overview

This Python-based interactive program provides a detailed, step-by-step explanation of the **Knapsack Problem**, implemented using **Dynamic Programming**. The code is designed to run on **Google Colab** and offers an educational experience by explaining each calculation in detail. It helps users understand how the dynamic programming approach solves the **0/1 Knapsack Problem** by showing the intermediate steps, decisions made at each step, and how the optimal solution is constructed.

## Features

- **Interactive Visualization:** The program walks through each step of the dynamic programming table construction.
- **Step-by-Step Calculations:** Every calculation made to determine the maximum value at each step is clearly displayed.
- **Comprehensive Explanation:** Detailed explanations are provided for each choice—whether an item is included or excluded from the knapsack.
- **Dynamic Programming Approach:** Uses a tabulation-based dynamic programming method to solve the knapsack problem, ensuring an efficient solution.
  
## Knapsack Problem

The Knapsack Problem is a classical optimization problem where you are given a set of items, each with a weight and a value, and a knapsack with a weight capacity. The goal is to determine the number of each item to include in the knapsack so that the total weight is less than or equal to the capacity, and the total value is maximized.

### Problem Formulation:
Given:
- A set of `n` items, each with:
  - `weight[i]`: the weight of the item
  - `value[i]`: the value of the item
- `W`: the maximum weight capacity of the knapsack.

Find the maximum total value of items that can be included in the knapsack without exceeding the weight capacity.

## How It Works

1. **Dynamic Programming Table Creation:**  
   The program constructs a 2D table where each cell `dp[i][w]` represents the maximum value that can be attained with the first `i` items and a knapsack capacity of `w`.

2. **Decision Making:**  
   At each step, the program decides whether to include or exclude the current item based on the value and weight constraints. These decisions are clearly shown to the user with an explanation.

3. **Backtracking to Find Solution:**  
   After the table is filled, the program backtracks through the table to determine which items were included in the optimal solution, providing users with the final selected items.

4. **Detailed Output:**  
   The program prints:
   - The dynamic programming table.
   - The intermediate steps of the algorithm.
   - The final selection of items with the total value and total weight.

## Usage Instructions

1. **Clone the Repository or Open in Colab**  
   To run the code, you can either clone this repository or open the Python notebook directly in Google Colab:
   - **Google Colab Link:** [Open in Google Colab](<Google Colab URL>)

2. **Install Necessary Libraries**  
   The code does not require any external libraries beyond the standard Python libraries. Simply run the notebook in Google Colab to get started.

3. **Run the Code**  
   Once in Colab, simply execute the cells in the notebook. The program will prompt you to enter:
   - Number of items.
   - Weight and value for each item.
   - Knapsack capacity.

4. **Understand the Output**  
   Follow the step-by-step explanation of the dynamic programming table and the final solution to understand how the algorithm works.

## Contact

If you have any questions, feel free to reach out:

- **Email:** [vishnutanpure@gmail.com](mailto:vishnutanpure@gmail.com)
- **GitHub:** [GitHub Profile](https://github.com/VishnuTanpure)
