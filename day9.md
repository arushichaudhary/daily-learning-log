## Day 9 — 2026-07-11

**Learned:**
- Reinforcement Learning: Started building a second RL project — a DQN agent for LunarLander using Gymnasium, extending what I learned from the CartPole project to a harder environment (8-dimensional state space, 4 actions, and reward shaping that penalizes crashing and rewards smooth landings).
- Realized different RL environments need different hyperparameters — LunarLander needed a bigger network, larger replay buffer, and more training episodes than CartPole since it's a harder problem.
- Aptitude: [topic covered today]

**Did:**
- Set up the LunarLander project structure (dqn_agent.py, train.py, evaluate.py, plot_results.py) reusing the DQN implementation from CartPole
- Ran initial test training to confirm the pipeline works end-to-end before a longer training run
- [Aptitude practice — e.g. "Solved X questions on Y topic"]
- [Any PR #33 follow-up, if applicable]

**Stuck on:**
- Longer training runs take a while to actually solve LunarLander (needs several hundred episodes), so still in progress
- [Anything else unresolved today]

**Tomorrow:**
- Finish training the LunarLander agent and generate the results plot
- Push both CartPole and LunarLander projects to GitHub
- [Next aptitude topic]

**Aptitude score/accuracy today:** [e.g. 7/10]

**Open source contributions merged so far:** 1 (2nd pending final merge)