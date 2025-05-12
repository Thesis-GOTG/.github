# MARBeL: A Model-based Approach using Recursive Belief-based Learning for Solving Imperfect Information Mind Sports
## 📑 Contents

- [Project Overview](#-project-overview)
- [Repositories Overview](#-repositories-overview)
- [Installation](#-installation)
- [Project Goal](#-project-goal)
- [Technologies](#-technologies)
- [Contributors](#-contributors)

## ℹ️ Project Overview
Welcome to the repository for the Senior thesis, MARBeL, which utilizes a model-based algorithm that combines self-play reinforcement learning and search to solve imperfect information
mind sports.

Games can be categorized based on the availability of information to players. In perfect information games such as Chess and Go, all players have complete knowledge of the game state at all
times. Advancements in artificial intelligence (AI) have led to superhuman-level chess engines such as AlphaZero and Stockfish, which not only surpass human players but also serve as essential tools for training and strategy development. 

Conversely, games such as Poker and Scrabble fall under the category of imperfect information games, where elements are hidden from one or more players. This uncertainty adds complexity to
decision-making and remains a significant challenge for AI. Traditional techniques like Monte Carlo Tree Search (MCTS) have proven effective in perfect information settings but struggle in games
where hidden information plays a crucial role.

Recent advancements, such as Recursive Belief-based Learning (ReBeL), have demonstrated the effectiveness of integrating reinforcement learning with search techniques to approximate Nash equi-libria in two-player zero-sum games. Building upon ReBeL, we introduce MARBeL, a model-based algorithm that combines self-play reinforcement learning and search to solve imperfect information
mind sports. MARBeL leverages convolutional neural networks (CNNs) for spatial feature extraction and recurrent neural networks (RNNs), specifically long short-term memory (LSTM) networks,
for temporal decision-making. Our research applies MARBeL to the Game of the Generals (GoG), a strategic board game characterized by hidden information and complex decision-making.

This project is divided into three distinct components:
1. [MARBeL Algorithm](https://github.com/Thesis-GOTG/MARBeL) – the proposed algorithm for solving imperfect information mind sports
2. [Training Repository](https://github.com/Thesis-GOTG/training) – contains the different model versions that were trained and their results
3. [Game of the Generals Game](https://github.com/Thesis-GOTG/gog) – Playable implementation of the Game of the Generals game using the trained model.


## 📁 Repositories Overview

## 🧰 Installation
## 🎯 Project Goal
## ⚒️ Technologies
## 👩‍💻🧑‍💻 Contributors

