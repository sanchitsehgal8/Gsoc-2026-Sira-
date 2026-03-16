# Gsoc-2026-Sira-
 SIRA 

This repository contains my completed evaluation test for the HumanAI Foundation GSoC project: Learning the Susceptible–Infected–Removed (SIR) Model.

The goal of this project is to simulate epidemic dynamics, process the generated data, and use machine learning and symbolic regression to rediscover the underlying differential equations governing disease spread.

📋 Project Overview

The workflow implemented in this evaluation test includes:

Stochastic Epidemic Simulation
Simulating epidemic outbreaks using the classical SIR (Susceptible–Infected–Removed) model.

Data Preprocessing
Cleaning and smoothing the simulated outbreak trajectories to make them suitable for machine learning.

Neural Network Modeling
Training neural networks to learn and approximate the trajectories of the SIR model.

Symbolic Regression
Using PySR to infer the underlying differential equations from the data.

This pipeline demonstrates how machine learning can rediscover known scientific laws from data, a core idea in scientific machine learning.

🧠 Technologies Used

Python 3.9

PyTorch – Neural network training

PySR – Symbolic regression (Julia backend)

NumPy – Numerical computing

Pandas – Data processing

Matplotlib – Visualization

Jupyter Notebook – Experimentation and documentation

🚀 How to Run
1️⃣ Clone the Repository
git clone <repository-link>
cd <repository-name>
2️⃣ Install Dependencies
pip install -r requirements.txt
3️⃣ Run the Notebook
jupyter notebook SIRA_evaluation_test.ipynb

The notebook contains the full pipeline, including simulation, preprocessing, neural network training, and symbolic regression.

📄 Repository Contents
File	Description
SIRA_evaluation_test.ipynb	Main notebook containing the full evaluation test and results



🔬 Key Concepts Demonstrated

Epidemiological modeling using the SIR framework

Stochastic simulation of epidemic outbreaks

Machine learning for trajectory prediction

Symbolic regression for equation discovery

Integration of ML and scientific modeling

📌 About the SIR Model

The SIR model is a classical epidemiological model that describes how infectious diseases spread through a population.

It divides the population into three compartments:

S (Susceptible) – individuals who can become infected

I (Infected) – individuals currently infected

R (Removed/Recovered) – individuals who have recovered or died

The model is governed by differential equations describing the transitions between these states.

🤝 Acknowledgement

This work was completed as part of the evaluation test for the HumanAI Foundation GSoC project on learning the SIR model.
