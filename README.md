# Adaptive Market Planning Model

This repository contains a Jupyter Notebook implementation of the Adaptive Market Planning model, a sequential decision-making framework for optimizing market planning decisions under uncertainty. The model incorporates adaptive learning to adjust the order quantities based on observed demand patterns.

The code leverages work by Prof. Warren Powell

Book: https://castle.princeton.edu/wp-content/uploads/2022/11/Powell-SDAM-Nov242022_final_w_frontcover.pdf

GitHub: https://github.com/wbpowell328/stochastic-optimization

## Table of Contents

- [Introduction](#introduction)
- [Model Components](#model-components)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Adaptive Market Planning model is a specific instance of Sequential Decision Analysis that focuses on optimizing market planning decisions, such as setting order quantities, in the presence of uncertain demand. The model aims to maximize the expected profit over a given time horizon by adapting the order quantities based on the observed outcomes.

## Model Components

The key components of the Adaptive Market Planning model include:

- State variables: Order quantity and counter
- Decision variables: Step size
- Exogenous information: Uncertain demand
- Transition function: Updates the state variables based on the current state, decision, and exogenous information
- Objective function: Maximizes the expected profit considering revenue and costs

The model incorporates adaptive learning using Kesten's rule to adjust the step size over time based on the observed demand patterns.

## Installation

To run the Adaptive Market Planning model notebook, you need to have the following dependencies installed:

- Python (version 3.6 or higher)
- Jupyter Notebook
- NumPy
- Matplotlib

You can install the required packages using pip:

```
pip install jupyter numpy matplotlib
```

## Usage

1. Clone the repository:

```
git clone https://github.com/your-username/adaptive-market-planning-model.git
```

2. Navigate to the repository directory:

```
cd adaptive-market-planning-model
```

3. Launch Jupyter Notebook:

```
jupyter notebook
```

4. Open the `adaptive_market_planning_model.ipynb` notebook in your browser.

5. Run the notebook cells to execute the code and observe the results.

## Results

The notebook provides the following results:

- Optimal order quantity for the given price and cost parameters
- Average reward over multiple iterations
- Plots visualizing the reward trends and the comparison of analytical and learned order quantities

## Contributing

Contributions to the Adaptive Market Planning model notebook are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to customize the README file based on your specific implementation and add any additional sections or information that you think would be helpful for users of your repository.
