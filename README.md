
# Probability and Statistics - University of Tehran

## Overview

This repository contains assignments for the **Probability and Statistics** course in the field of **Computer and Electrical Engineering** at the **University of Tehran**. These assignments are designed to deepen the understanding of probability theory, statistical methods, and their applications using Python. Each assignment focuses on specific concepts, such as distributions, hypothesis testing, sampling, and estimation.

---

## Repository Structure

### Computational Assignments (`CAs/`)

- **CA#0**: [Bayes&#39; Theorem and Python Basics](#ca-0---bayes-theorem-and-python-basics)
- **CA#1**: [Bernoulli and Binomial Distributions](#ca-1---bernoulli-and-binomial-distributions)
- **CA#2**: [Probability Distributions and Data Analysis](#ca-2---probability-distributions-and-data-analysis)
- **CA#3**: [Regression, Sampling, and Mean Squared Error (MSE)](#ca-3---regression-sampling-and-mean-squared-error-mse)

### Homework Assignments (`HWs/`)

- **HW#0**: [Conditional Probability and Combinatorics](#hw-0---conditional-probability-and-combinatorics)
- **HW#1**: [Discrete Probability and Expectation](#hw-1---discrete-probability-and-expectation)
- **HW#2**: [Continuous Distributions and Expectation](#hw-2---continuous-distributions-and-expectation)
- **HW#3**: [Joint Distributions and Independence](#hw-3---joint-distributions-and-independence)
- **HW#4**: [Covariance and Moment Generating Functions](#hw-4---covariance-and-moment-generating-functions)
- **HW#5**: [Conditional Expectation and Poisson Processes](#hw-5---conditional-expectation-and-poisson-processes)
- **HW#6**: [Central Limit Theorem and Chebyshev&#39;s Inequality](#hw-6---central-limit-theorem-and-chebyshevs-inequality)
- **HW#7**: [Confidence Intervals and Hypothesis Testing](#hw-7---confidence-intervals-and-hypothesis-testing)

---

## Assignment Descriptions

### Computational Assignments (CAs)

#### CA #0 - **Bayes' Theorem and Python Basics**

This assignment introduces the use of Python for solving probability problems using Bayes' Theorem. It emphasizes the application of Naive Bayes classifiers for text classification.

- **Topics Covered:**
  - Introduction to Bayes' Theorem and its applications.
  - Text preprocessing using libraries like **Hazm** for Persian text.
  - Implementing a text classification algorithm using the **Bag of Words** method.
  - Applying additive smoothing techniques to improve classification accuracy.

---

#### CA #1 - **Bernoulli and Binomial Distributions**

This assignment focuses on the relationship between Bernoulli and Binomial distributions.

- **Topics Covered:**
  - Understanding the connection between repeated Bernoulli trials and their binomial outcomes.
  - Writing Python functions to simulate binomial trials and generate samples.
  - Visualizing the variance and mean of these samples using different values of \( p \) (probability of success).
  - Approximating the binomial distribution using Poisson and normal distributions under certain conditions.

---

#### CA #2 - **Probability Distributions and Data Analysis**

This assignment delves into advanced concepts in probability.

- **Topics Covered:**
  - Working with datasets related to real-world scenarios (e.g., transportation datasets involving metro and bus traffic).
  - Exploring distributions of random variables using histograms and density plots.
  - Applying theoretical distribution models (e.g., normal, Poisson) to real-world data.
  - Combining multiple distributions into new variables and analyzing their properties.

---

#### CA #3 - **Regression, Sampling, and Mean Squared Error (MSE)**

This assignment addresses multiple statistical concepts.

- **Topics Covered:**
  - Linear regression and least squares methods.
  - Investigating the impact of outliers and high-leverage points on regression models.
  - Working with sampling techniques and the **Central Limit Theorem**.
  - Implementing an autoencoder neural network for image reconstruction (using the **MNIST** dataset) and evaluating its performance using MSE.
  - Conducting hypothesis tests to assess the normality of residuals in regression models.

---

### Homework Assignments (HWs)

#### HW #0 - **Conditional Probability and Combinatorics**

- **Topics Covered:**
  - **Combinatorics**: Counting methods for seating arrangements and card games.
  - **Conditional Probability**: Calculations with conditions, like adjacent individuals or prior events.
  - **Markov Processes**: Recursive decision-making scenarios (e.g., pencil selection problem).

---

#### HW #1 - **Discrete Probability and Expectation**

- **Topics Covered:**
  - **Expected Value and Variance**: Applications in games of chance and letter distribution problems.
  - **Geometric and Binomial Distributions**: Modeling repeated trials until success.
  - **Derangements**: Permutations where no object appears in its original position.

---

#### HW #2 - **Continuous Distributions and Expectation**

- **Topics Covered:**
  - **Continuous Probability Distributions**: Modeling time-related problems like waiting times.
  - **Transformation of Random Variables**: Converting one distribution into another.
  - **Exponential and Uniform Distributions**: Practical applications in arrival times.

---

#### HW #3 - **Joint Distributions and Independence**

- **Topics Covered:**
  - **Joint Distributions**: Determining marginal and conditional distributions for pairs of variables.
  - **Covariance and Independence**: Analyzing relationships between random variables.
  - **Exponential Distributions**: Modeling the timing of simultaneous events.

---

#### HW #4 - **Covariance and Moment Generating Functions**

- **Topics Covered:**
  - **Moment Generating Functions**: Tools for finding expected values and higher moments.
  - **Covariance**: Measuring the degree to which two variables change together.
  - **Conditional Distributions**: Calculating probabilities given specific conditions.

---

#### HW #5 - **Conditional Expectation and Poisson Processes**

- **Topics Covered:**
  - **Poisson Processes**: Modeling random events occurring over time (e.g., customer arrivals).
  - **Law of Total Probability**: Applying to conditional distributions and expectations.
  - **Uniform Distributions**: Modeling independent random variables within a range.

---

#### HW #6 - **Central Limit Theorem and Chebyshev's Inequality**

- **Topics Covered:**
  - **Chebyshev’s Inequality**: Bounding the probability of deviations from the mean.
  - **Central Limit Theorem**: Understanding the distribution of sample means.
  - **Unbiased Estimators**: Identifying estimators with minimal variance.

---

#### HW #7 - **Confidence Intervals and Hypothesis Testing**

- **Topics Covered:**
  - **Maximum Likelihood Estimation (MLE)**: Techniques for parameter estimation.
  - **Confidence Intervals**: Constructing intervals to estimate population parameters with a given level of confidence.
  - **Hypothesis Testing**: Procedures for testing assumptions about population parameters, including Type I and II errors.

---

## How to Run

To execute the assignments and exercises:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/tahamajs/Probability_Statistics_Course.git
   ```
2. **Navigate to the project directory:**

   ```bash
   cd probability-statistics-assignments
   ```
3. **Install the necessary libraries:**

   ```bash
   pip install -r requirements.txt
   ```

---

## Requirements

Ensure you have the following Python libraries installed:

- **Python 3.x**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **SciPy**
- **Scikit-learn**
- **TensorFlow** (for neural network implementations)
- **Hazm** (for Persian text processing)

You can install all required packages using:

```bash
pip install -r requirements.txt
```

---

## License

This repository is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.

---

## Acknowledgements

- **Course:** Probability and Statistics
- **University:** University of Tehran
- **Field:** Computer and Electrical Engineering

