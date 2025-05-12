# MARBeL: A Model-based Approach using Recursive Belief-based Learning for Solving Imperfect Information Mind Sports
## 📑 Contents

- [Project Overview](#-project-overview)
- [Installation](#-installation)
- [Project Goal](#-project-goal)
- [Contributors](#-contributors)

## ℹ️ Project Overview
Welcome to the repository for the Senior thesis, MARBeL, which utilizes a model-based algorithm that combines self-play reinforcement learning and search to solve imperfect information
mind sports.

Games can be categorized based on the availability of information to players. In perfect information games such as Chess and Go, all players have complete knowledge of the game state at all
times. Advancements in artificial intelligence (AI) have led to superhuman-level chess engines such as AlphaZero and Stockfish, which not only surpass human players but also serve as essential tools for training and strategy development. 

Conversely, games such as Poker and Scrabble fall under the category of imperfect information games, where elements are hidden from one or more players. This uncertainty adds complexity to
decision-making and remains a significant challenge for AI. Traditional techniques like Monte Carlo Tree Search (MCTS) have proven effective in perfect information settings but struggle in games
where hidden information plays a crucial role.

Recent advancements, such as Recursive Belief-based Learning (ReBeL), have demonstrated the effectiveness of integrating reinforcement learning with search techniques to approximate Nash equilibria in two-player zero-sum games. Building upon ReBeL, we introduce MARBeL, a model-based algorithm that combines self-play reinforcement learning and search to solve imperfect information
mind sports. MARBeL leverages convolutional neural networks (CNNs) for spatial feature extraction and recurrent neural networks (RNNs), specifically long short-term memory (LSTM) networks,
for temporal decision-making. Our research applies MARBeL to the Game of the Generals (GoG), a strategic board game characterized by hidden information and complex decision-making.

This project is divided into three distinct components:
1. [MARBeL Algorithm](https://github.com/Thesis-GOTG/MARBeL) – the proposed algorithm for solving imperfect information mind sports
2. [Training Repository](https://github.com/Thesis-GOTG/training) – contains the different model versions that were trained and their results
3. [Game of the Generals Game](https://github.com/Thesis-GOTG/gog) – Playable implementation of the Game of the Generals game using the trained model.

## 🧰 Installation
1. Clone the repositories (skip if you already have the copies):
```
git clone git@github.com:Thesis-GOTG/MARBeL.git
git clone git@github.com:Thesis-GOTG/training.git
git clone git@github.com:Thesis-GOTG/gog.git
```
2. Make sure that the 3 repositories are under one folder, like so:
```
  marbel-thesis-project/
  ├── MARBeL/  
  ├── training/   
  ├── gog/
  └── README.md
```
3. View and follow the respective <code>README.md</code> files inside each repository to setup the project

## 🎯 Project Goal
Through MARBeL, we aim to advance AI strategies for reasoning under uncertainty in competitive environments. We envision that MARBeL’s belief-based reasoning could significantly enhance AI’s ability to model opponent behavior and strategic deception. These capabilities are not only valuable in gaming but also in real-world applications.

## 👩‍💻🧑‍💻 Contributors
**Proponents:**
- [Angeline B. Basbas](https://github.com/StrayMarimo): 4 - BS Computer Science, Ateneo de Naga University
- [Justin Ira A. Natividad](https://github.com/Evil-Jian): 4 - BS Computer Science, Ateneo de Naga University
  
**Adviser**: 
[Kevin G. Vega](https://github.com/kgvega-adnu): CCS Faculty, Ateneo de Naga University



