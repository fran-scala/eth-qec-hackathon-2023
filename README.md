# IQM-Challenge

## C-NOTpolitecnico
This repository contains all the materials for the 2023 ETH Zurich Quantum Hackathon and IQM-Challenge about exploting symmetries in quantum machine learning.

## Folders
### Tic-tac-toe
This folder contains all the Python code for the tic-tac-toe problem. The sub-folders are `non symmetric`, `partially symmetric`, and `symmetric`. These folders contain the results from different quantum neural network layouts.

In addition, you have three Jupyter Notebook files used to generate the respective results:

- `tic_tac_toe_partially_symm.ipynb`
- `tic_tac_toe_random_QNN.ipynb`
- `tic_tac_toe_symm.ipynb`

##### Highlight
Thanks to the particular libraries employed we were able to have high performance simulations like the symmetric QNN with 4 layers and 4 sublayers that the authors of the [paper](https://journals.aps.org/prxquantum/pdf/10.1103/PRXQuantum.4.010328) were not able to simulate

### Schwinger
This folder contains all the Python code for the Quantum Field theory analysis using geometric quantum machine learning techniques. The sub-folders are `asymmetric` and `symmetric`, which contain the results from the experiments.

In addition, you have three iPython files used to run the experiments:

- `Schwinger_circuit_asym.ipynb`
- `Schwinger_circuit.ipynb`
- `Generator.ipynb`

The Generator.ipynb file is used to generate the dataset.

### Extra foleders
The repository also contains the original .zip file of the challenge and the correspondant folder: `eth-qec-hackathon-2023-main`

### Presentation
`Qhack_Presentation.pdf` is a slide presentation summing up the main results of the project.

## Getting Started
To get started with this repository, simply clone it to your local machine using the following command:

git clone https://github.com/fran-scala/C-NOTpolitecnico.git

Once you have cloned the repository, you can navigate to the relevant folder to access the Python code.

## Libraries

Particular libraries required are: `pennylane`, `jax` and `optax`. If you need to install them you can just do it by typing the following lines in your terminal:

```
pip install pennylane
pip install jax
pip install optax
```

Pennylane is a quantum computing library designed for variational quantum algorithms and quantum machine learning. JAX is NumPy on the CPU, GPU, and TPU, with great automatic differentiation for high-performance machine learning research and Optax is a gradient processing and optimization library for JAX.


