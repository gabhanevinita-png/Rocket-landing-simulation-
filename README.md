# 🚀 Rocket Landing AI using Reinforcement Learning

## Overview
This project trains an AI agent to autonomously land a lunar spacecraft using Reinforcement Learning. The agent learns how to control the rocket's engines, manage movement, reduce velocity, and attempt safe landings through repeated interactions with a simulated environment.

## 🎯 Objective
Train an intelligent agent to land a lunar lander safely by learning optimal actions through trial and error, using reward shaping to encourage better flight behavior.

## 🧠 Technologies Used
- Python
- Gymnasium (LunarLander-v3)
- Stable-Baselines3
- PPO (Proximal Policy Optimization)
- NumPy
- Matplotlib
- Google Colab

## ⚙️ Methodology
1. Created a LunarLander simulation environment.
2. Analyzed the 8-dimensional state space.
3. Implemented a custom reward-shaping wrapper.
4. Trained an agent using PPO.
5. Continued training to 300,000 timesteps.
6. Evaluated the trained agent across 5 episodes.
7. Visualized evaluation rewards.

## 🏆 Evaluation Results

| Metric | Result |
|---|---:|
| Evaluation episodes | 5 |
| Average reward | 10.14 |
| Detected successful landings | 1/5 |
| Estimated success rate | 20% |

*Results are from a small evaluation sample. The landing detector may misclassify outcomes, and further evaluation is needed.*

## 💡 Key Learning
- Reinforcement Learning fundamentals
- PPO policy optimization
- Reward shaping
- Environment wrappers
- State and action spaces
- Model evaluation
- Visualization of agent performance

## 🚧 Future Improvements
- Improve reward shaping
- Evaluate over more episodes
- Compare shaped and unshaped agents
- Improve landing-success detection
- Optimize training performance

## 👨‍💻 Author
CSE – Artificial Intelligence & Machine Learning
