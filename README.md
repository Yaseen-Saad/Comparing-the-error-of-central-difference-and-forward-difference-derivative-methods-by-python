# Derivative Approximation and Error Analysis

This project demonstrates derivative approximation techniques (forward difference and central difference) for the sine function, along with error analysis. The relative errors of these approximations are visualized using a logarithmic scale, allowing for a detailed comparison across different step sizes.

## Table of Contents
- [Project Overview](#project-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Code Structure](#code-structure)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This project explores numerical differentiation by approximating the derivative of the sine function using forward and central difference methods. The relative errors of each approximation are plotted against the exact derivative values to understand how the error varies with different step sizes (`dx` values).

## Installation

1. Clone this repository:
    ```bash
    git clone <repository_url>
    cd <repository_directory>
    ```

2. Install the required Python packages:
    ```bash
    pip install sympy numpy matplotlib tqdm
    ```

## Usage

Run the code using Python:

```bash
python derivative_approximation.py
