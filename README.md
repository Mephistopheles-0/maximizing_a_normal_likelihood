# Normal Likelihood Maximization and Likelihood Plotting

## Overview

This R program demonstrates the process of maximizing a normal likelihood function using the `optim` and `optimize` functions. It also includes functionality to plot the likelihood function for different scenarios.

## Usage

### Installation

1. Make sure you have R installed on your system. If not, you can download it from [R Project](https://www.r-project.org/).

2. Clone or download this repository to your local machine.

### Running the Program

1. Open R or RStudio.

2. Set your working directory to the location where you have saved the program files.

3. Open the R script `maximize_and_plot_normal_likelihood.R`.

4. You can run the entire script or specific sections as needed.

### Description

- `make.NegLogLik` function:
  - This function creates a negative log-likelihood function for a normal distribution.
  - Parameters:
    - `data`: The dataset for which you want to maximize the likelihood.
    - `fixed`: A vector indicating which parameters (mean and standard deviation) should be fixed during optimization.

- `normals`:
  - A random dataset generated using the `rnorm` function to serve as an example data for likelihood maximization.

- Estimating Parameters:
  - The script demonstrates two scenarios:
    1. Maximizing the likelihood to estimate both mean (`mu`) and standard deviation (`sigma`) using the `optim` function.
    2. Fixing one parameter (`sigma` or `mu`) and maximizing the likelihood for the other using the `optimize` function.

- Plotting The Likelihood:
  - The script includes examples of plotting the likelihood function for fixed parameters.
  - You can visualize how the likelihood changes for different parameter values.

## Results

The script will output the estimated parameters (`mu` and `sigma`) or the optimized parameter value (in the case of fixed parameters) to the R console. Additionally, it will produce likelihood plots for the specified scenarios.

## Dependencies

This program requires R to be installed on your system. There are no external packages or dependencies needed.

## License

This program is provided under the [MIT License](LICENSE).

## Author

- [A.HAIDA]

Feel free to reach out if you have any questions or need further assistance.
