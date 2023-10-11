## Project-3-secret-sharing

This README provides instructions on how to run the Secure Multi-Party Computation (SMPC) runtime experiment code. The experiment measures the runtimes for three different SMPC approaches: **No Privacy Protection**, **Shamir's Secret Sharing**, and **Paillier Encryption**, across various values of `n`.

### Prerequisites

Before running the code, make sure you have the following prerequisites installed:

Python 3.x
Jupyter Notebook installed
Required Python libraries (You can install them using `pip install <library_name>`):

`plotly`

`sympy`

`phe`

### Getting Started

1. Clone this repository:

```bash
git clone https://github.com/harisiqbal10/Project-3-secret-sharing.git
cd Project-3-secret-sharing
```
2. Launch the Jupyter Notebook
   
3. Open the code file, `Project_3_Secret_Sharing.ipynb`, and update the following variables to customize your experiment:

`values_of_n`: List of `n` values for which you want to measure runtimes.
`num_experiments`: Number of experiments to run for each `n`.
`values_per_party`: The number of values generated for each party in each experiment.
Modify `secret` in the `shamir_secret_sharing` function if you want to use a different secret.
