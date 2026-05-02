# SUMO Traffic Signal Control with PPO

A reinforcement learning project that optimizes traffic signal timing at a 4-way intersection using **Proximal Policy Optimization (PPO)** and the **SUMO (Simulation of Urban Mobility)** traffic simulator.

The PPO agent dynamically adjusts signal phases based on real-time vehicle queue lengths, reducing intersection clearance time for 500 vehicles from **1999 seconds** (fixed-time baseline) to **1150 seconds** — roughly a **42% improvement**.

---

## Tech Stack

- **SUMO** — traffic simulation environment
- **TraCI** — real-time SUMO control via Python
- **Stable-Baselines3** — PPO implementation
- **Gymnasium** — custom RL environment wrapper
- **PyTorch** — underlying deep learning backend

---

## Results

| Method | Time (500 vehicles) |
|--------|---------------------|
| Fixed-time signal | 1999 s |
| PPO-optimized | 1150 s |
| **Improvement** | **~42% faster** |

---

## Quick Start

```bash
# Install dependencies
pip install stable-baselines3 gymnasium torch traci sumolib

# Train the agent
python traffic_agent.py

# Evaluate with GUI
python test_model.py
```

> Requires [SUMO](https://eclipse.dev/sumo/) to be installed and `SUMO_HOME` set.

---

# Machine Learning Sessional

A collection of hands-on ML lab notebooks covering core machine learning concepts and algorithms, completed as part of the CSE Machine Learning Sessional course at MIST.

## Labs

| Lab | Topic |
|-----|-------|
| Day 1 | Iris species classification using Random Forest |

## Tech Stack

- **scikit-learn** — ML models and evaluation
- **pandas / numpy** — data handling
- **Jupyter Notebook** — lab environment

---
