# Quantum Computing Lecture 1: Introduction to Qiskit and Quantum Circuits

## Lecture Content

- **`lecture_1.ipynb`**: This Jupyter Notebook contains the code and explanations covered in this lecture. You will find step-by-step instructions on installing the necessary libraries, creating a basic quantum circuit, and visualizing it.

## Getting Started with Colab

To make it easy for you to follow along and execute the code on your own machine, we recommend using Google Colab, a cloud-based Jupyter Notebook platform. Here are the basic steps to access the Colab notebook:

1. **Create a Google Account:** If you don't have one already, create a Google account at [Google Account Sign-up](https://accounts.google.com/signup).

2. **Open the Colab Notebook:** Click on the following link to open the Colab notebook for this lecture:

3. **Run the Notebook:** Once the Colab notebook is open, click on "File" > "Save a copy in Drive" to create your own copy. You can now run the code cells, experiment, and learn interactively.

## Dependencies

Before you can run the code in the notebook, make sure you have the following libraries installed within the notebook using `!pip install`:

- [Qiskit](https://qiskit.org/): A comprehensive quantum computing library for Python. 
  !pip install qiskit

- Qiskit-Aer: Qiskit's high-performance simulator framework. This allows us to access various simulators that would required to execute our quantum circuit.
  !pip install qiskit-aer
  
- Pylatexenc: A Python library for encoding and decoding LaTeX-encoded strings. This allows us to visualize the quantum circuits in colab notebook.
  !pip install pylatexenc
