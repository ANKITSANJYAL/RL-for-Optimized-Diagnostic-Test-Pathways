# RL-for-Optimized-Diagnostic-Test-Pathways
## 🧠 Project 2: RL for Optimized Diagnostic Test Pathways

### 📌 Problem Statement
In clinical practice, doctors must select the right sequence of diagnostic tests to reach a confident diagnosis quickly and cost-effectively. However, these decisions are often made heuristically. This project leverages reinforcement learning to learn an optimal policy for test selection, minimizing unnecessary testing while maximizing diagnostic accuracy.

### 🎯 Goals
- Simulate a diagnostic environment with patient states and test actions
- Train an RL agent to select tests sequentially
- Evaluate tradeoffs between cost, accuracy, and speed
- Visualize learned policies and decision pathways

### 🧠 Tech Stack
- **Simulation Env**: Custom OpenAI Gym environment (simulating patients/tests)
- **RL Algorithms**: Q-Learning, Deep Q-Network (DQN)
- **Libraries**: NumPy, PyTorch, Gym, Matplotlib, Seaborn
- **Explainability**: Policy trace plots, reward evolution, decision tree comparison (optional)

### 🏗️ Project Structure
```
diagnostic-rl-agent/
├── envs/               # Custom Gym environment simulating patient-test interactions
├── agents/             # Q-learning and DQN implementations
├── experiments/        # Training configs, logs, reward tracking
├── notebooks/          # Policy visualizations, evaluation, ablations
├── app/                # Optional visualization dashboard
├── README.md
```

---
