# UFRGS – Artificial Intelligence Assignment 2

**Course:** Artificial Intelligence (INF01048)  
**Institution:** Federal University of Rio Grande do Sul (UFRGS)  
**Professor:** Joel Luís Carbonera  
**Department:** Applied Informatics, Institute of Informatics  

## 🧑‍💻 Group Members

- João Francisco Hirtenkauf Munhoz – 00275634  
- Luís Antônio Mikhail Dawa – 00313853  
- Mario Augusto Brum da Silveira – 00322868  

---

## 📍 Assignment Overview

This assignment focuses on Reinforcement Learning and is divided into two main parts:

1. **Value Iteration**

   Implementation of a value iteration agent that solves known MDPs (Markov Decision Processes) in the Gridworld environment.

   Edited File:
   - `valueIterationAgents.py`: contains the implementation of the value iteration algorithm.

2. **Q-learning**

   Implementation of Q-learning agents to learn from interaction with environments including:
   - Gridworld
   - Simulated robotic controller (Crawler)
   - Pacman game

   Edited Files:
   - `qlearningAgents.py`: contains Q-learning agents with ε-greedy policies and approximate Q-learning using feature extractors.
   - `analysis.py`: answers to analytical questions about the learned policies and behavior.

### Testing and Evaluation

We used the provided autograder to validate our implementation locally. Commands used include:
```bash
python autograder.py          # runs all questions
python autograder.py -q q2    # runs a specific question
python autograder.py -t test_cases/q2/1-bridge-grid  # runs a specific test
