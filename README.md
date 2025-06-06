# Reinforcement Learning-Based AI for Boss Behavior in Dark Souls-Inspired Environments

This project explores a novel approach to designing artificial intelligence (AI) for boss characters in games inspired by the **Dark Souls** series. Traditional AI models for such bosses typically rely on hierarchical probabilistic structures, resulting in predictable patterns and limited adaptability. Our goal is to enhance behavioral complexity and replayability by leveraging **reinforcement learning (RL)**.

## Overview

Instead of using hand-crafted behavior trees or probability-driven states, this project implements an RL model that learns from a custom simulation environment built in the **Godot engine**. The boss agent adapts dynamically to player actions through a system of:

- **Rewards and penalties**
- **Real-time observations**
- **Emergent traits**, such as aggression or passivity

This method allows AI behavior to evolve rather than be pre-scripted, enabling more nuanced and less predictable encounters.

## Key Features

- 🧠 **Reinforcement learning-based decision system**
- 🎮 **Custom training environment using Godot**
- 📈 **Quantitative and qualitative evaluation of behavior**
- 🧪 **Multiple experiments**, with the second showing the most promising results
- 📂 Modular structure for easy extensibility and experimentation

## Installation

To set up and run this project, please refer to the [`INSTALL.md`](./INSTALL.md) file for step-by-step instructions on installing dependencies, configuring the Godot project, and running the training environment.

## Folder Structure
```bash
├── RLAgent/ # Reinforcement learning logic
├── GodotEnv/ # Godot engine project (simulation environment)
├── data/ # Logs and evaluation data
├── experiments/ # Scripts and configs for various training runs
├── INSTALL.md # Installation instructions
├── README.md # You're here!
└── LICENSE
```


## Citation

If you use or build upon this project in your own work, please consider citing the accompanying article:

> This study proposes a reformulation of the artificial intelligence (AI) systems controlling boss characters in the Dark Souls game series. [...] Qualitative and quantitative evaluations demonstrated the feasibility of this approach, with the second experiment yielding the most favorable results in both assessments.

---

👨‍💻 Made with a passion for games and AI.
