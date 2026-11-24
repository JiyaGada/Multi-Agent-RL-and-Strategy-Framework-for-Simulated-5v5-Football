# Project Resources & Weekly Roadmap

Welcome! This document serves as the central hub for reading materials, tutorials, setup instructions, and weekly milestones. It will be updated periodically as we progress through the 6-week project.

## Week 0.5: Onboarding, Setup & RL Basics

### 1. Environment Setup

If you are on Windows, please install **WSL (Ubuntu)** before setting up your Python environment.

```bash
# Create and activate a virtual environment
python3 -m venv rl_env
source rl_env/bin/activate

# Install core libraries
pip install numpy matplotlib gymnasium

# Install PyTorch:
# - If you have an NVIDIA GPU (or are on macOS):
pip install torch

# - If you are on a CPU-only Linux/WSL machine (smaller & faster download):
pip install torch --index-url https://download.pytorch.org/whl/cpu
```

### 2. Reading & Tutorials

* **RL Intuition & MDPs:** [Hugging Face Deep RL Course – Unit 1 (Introduction to Deep RL)](https://huggingface.co/learn/deep-rl-course/en/unit1/introduction)

* **Environment API:** [Gymnasium Documentation & Tutorials](https://gymnasium.farama.org/tutorials/index.html)

* **PyTorch Refresher (Optional):** [PyTorch – Learn the Basics](https://docs.pytorch.org/tutorials/beginner/basics/intro.html)

### 3. Mini-Task

* Write a short Python script that runs a random agent in Gymnasium (`FrozenLake-v1` or `CartPole-v1`) to familiarize yourself with `env.reset()`, `env.step(action)`, `terminated`, and `truncated`.

## Week 1: Tabular Q-Learning & Football Baseline

### 1. Reading & Lectures

* **Q-Learning Theory & Code:** [Hugging Face Deep RL Course – Unit 2 (Introduction to Q-Learning)](https://huggingface.co/learn/deep-rl-course/en/unit2/introduction)

* **Deeper Mathematical Foundations:** [David Silver's RL Course – Lectures 1 & 2 (Intro to RL & MDPs)](https://www.youtube.com/playlist?list=PLzuuYNsE1EZAXYR4FJ75jcJseBmo4KQ9-)

### 2. Simulator Setup

> *Setup instructions and starter repository links for the 5v5 football simulator will be added here at the start of Week 1.*

### 3. Week 1 Deliverables

1. **Tabular Q-Learning:** Implement Q-Learning from scratch in NumPy on `FrozenLake-v1` and plot the rolling average reward over episodes.

2. **Heuristic Football Agent:** Run the simulator, inspect the observation/action spaces, and build a basic rule-based (FSM) agent that can play a full match against the starter bot without crashing.

## Week 2: Deep Q-Networks (DQN) & Reward Shaping

*Resources and milestones to be added.*

## Week 3: Policy Gradients & Proximal Policy Optimization (PPO)

*Resources and milestones to be added.*

## Weeks 4–5: Multi-Agent Strategy, Team Coordination & Self-Play

*Resources and milestones to be added.*

## Week 6: Head-to-Head Tournament & Final Report

*Tournament rules, submission format, and evaluation metrics to be added.*

## Reference Textbooks (Optional)

* *Reinforcement Learning: An Introduction* (2nd Edition) — Richard S. Sutton & Andrew G. Barto *(Chapters 1–3 for Week 1 foundations)*