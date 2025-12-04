Self-Supervised Learning for Real-Time Data Streams

This repository contains the research work and experiments for my paper “Self-Supervised Learning for Real-Time Data Streams.”
The project explores how machine learning models can learn and adapt from unlabeled, continuously changing data, which is common in IoT devices, smart cities, healthcare monitoring, and cybersecurity systems.

The main goal of this work is to design and test a simple and practical SSL framework that can learn from streaming data, handle concept drift, and detect anomalies without relying on human-labeled datasets.

What’s Included

  Full research paper (PDF + diagrams)

  Synthetic data experiment with concept drift

  Real-world experiment using the NYC Taxi dataset

  SSL model implementation (masked reconstruction + predictive coding)

  Autoencoder and supervised baselines for comparison

  Results and charts showing model performance

This project is meant to be easy to read, easy to run, and easy to understand for students, researchers, and anyone interested in self-supervised or streaming machine learning.

How to Run the Experiments

Install Python 3.8+

Install required packages:

pip install -r requirements.txt


Open the notebooks:

jupyter notebook


Run:

synthetic_experiment.ipynb

realworld_experiment.ipynb

Both notebooks include all steps, comments, and visualizations.

Repository Structure
paper/         # Full research paper and diagrams
code/          # Experiments and model implementations
data/          # Synthetic and real-world datasets
README.md

Purpose of This Work

This project was created to:

Explore how SSL can work in real-time systems

Compare SSL with supervised and autoencoder models

Understand challenges like concept drift

Provide a clean, human-friendly research example

The work is also prepared for journal submission.

Author

Punan Chowdhury
GitHub: your-username

If you find this work useful or interesting, feel free to star the repo.
