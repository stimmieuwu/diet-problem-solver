# Diet Problem Solver
**In partial fulfillment of the requirements for CMSC 150 - Numerical and Symbolic Computation**

This R Shiny application helps users find the cheapest combination of foods that meet their daily nutritional requirements. By utilizing linear programming, particularly the Simplex Method, we can apply this to any number of food items, nutritional restrictions, and serving count limitations.
Nutrient data is sourced from a database given by the lab instructor.
This project is the culmination of our lessons in numerical methods, from the basics of mathematical modeling to optimization and interpolation.
Being a solo project, this would not have been possible without my lab instructor LKLactuan and lecturer ABDoria.

## Features

* **Interactive Food Selection:** Choose from a variety of food items with a user-friendly interface.
* **Cost Optimization:**  Finds the most affordable combination of foods that satisfy the nutritional constraints.
* **Clear Results:** Displays the optimal diet in a table, showing the food items and their respective servings.
* **Visualization:** Presents the nutrient intake of the diet in a handy diagram.

## Getting Started

1. **Clone the repository:** `git clone https://github.com/your-username/diet-problem-solver.git`
2. **Install required packages:** Make sure you have the necessary R packages installed (i.e. `shiny`).
3. **Run the app:** Open the `app.R` file in RStudio and click "Run App".

## Usage

1. **Select Food Items:**  Use the checkboxes or search bar to select the foods you want to include in your diet.
2. **Solve:** Click the "Solve" button to run the optimization.
3. **View Results:** The optimal diet will be displayed in a table, showing the food items and their serving sizes.

## How It Works

Simplex
