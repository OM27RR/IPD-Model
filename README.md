# IPD Move Prediction using Neural Networks

## 📌 Overview

This project focuses on predicting the **next move in the Iterated Prisoner’s Dilemma (IPD)** using a **neural network–based model**. The goal is to learn strategic patterns from past interactions and accurately predict whether a player will **Cooperate (C)** or **Defect (D)** in the next round.

## 🎯 Objective

* Model player behavior in IPD using historical move sequences
* Predict the next action based on previous rounds
* Analyze how past strategies influence future decisions

## 🧠 Approach

* Generate or load IPD interaction data
* Encode past moves and payoff-related features
* Train a neural network to learn sequential decision patterns
* Evaluate prediction performance using accuracy and confidence scores

## 📊 Dataset Description

The dataset consists of repeated IPD rounds between players and includes:

* Previous moves of Player A and Player B
* Encoded cooperation/defection history
* Optional payoff or cumulative score features
* Target label: next move (C or D)

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* PyTorch / Neural Network framework
* Scikit-learn
* Jupyter Notebook

## 🔁 Workflow

1. Data generation or loading
2. Feature encoding of past moves
3. Neural network model design
4. Model training and validation
5. Performance evaluation

## 📈 Results

The neural network demonstrates the ability to capture strategic dependencies in IPD games and predict next-move behavior with meaningful accuracy, indicating learned patterns rather than random guessing.

## 📎 Notes

* This project focuses on **prediction**, not direct reinforcement learning
* Model performance depends on history length and data variability
* Randomness in strategies can affect achievable accuracy

## 🚀 Future Improvements

* Use LSTM / RNN models for better sequence learning
* Extend to multi-agent or population-based IPD
* Compare with reinforcement learning approaches
* Strategy classification instead of move prediction

## 🧑‍💻 Author

Om Gupta
