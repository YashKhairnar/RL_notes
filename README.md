# RL_notes

Deep research study notes, mathematical derivations, pseudocode, and intuitive diagrams based on Richard S. Sutton and Andrew G. Barto's *Reinforcement Learning: An Introduction* (2nd Edition).

## Live Site
The notes are deployed as a standalone, mobile-responsive visual website via GitHub Pages:  
👉 **[https://yashkhairnar.github.io/RL_notes/](https://yashkhairnar.github.io/RL_notes/)**

---

## Book Structure & Progress (5 / 17 Chapters)

### Part I: Tabular Solution Methods
- [ ] Chapter 1: Introduction *(Upcoming)*
- [ ] Chapter 2: Multi-arm Bandits *(Upcoming)*
- [x] **[Chapter 3: Finite Markov Decision Processes](docs/chapter_3_finite_markov_decision_processes_sutton_barto_2nd_ed.html)**
  - Agent-environment interface, Markov property, return & discounting, value functions, Bellman expectation & optimality equations, backup diagrams.
- [x] **[Chapter 4: Dynamic Programming](docs/chapter_4_dynamic_programming_sutton_barto_2nd_ed.html)**
  - Model-based planning: policy evaluation, policy improvement theorem, policy iteration, value iteration, asynchronous DP, and Generalized Policy Iteration (GPI).
- [x] **[Chapter 5: Monte Carlo Methods](docs/chapter_5_monte_carlo_methods_sutton_barto_2nd_ed.html)**
  - Model-free learning from experience: first-visit vs. every-visit MC, MC with exploring starts, on-policy $\varepsilon$-soft control, off-policy prediction via ordinary/weighted importance sampling, incremental implementation.
- [x] **[Chapter 6: Temporal-Difference Learning](docs/chapter_6_temporal_difference_learning_sutton_barto_2nd_ed.html)**
  - The central idea of RL: TD(0) prediction, TD error $\delta_t$, advantages of TD over DP and MC, Sarsa (on-policy control), Q-learning (off-policy control), Expected Sarsa, and Double Q-learning (maximization bias).
- [x] **[Chapter 7: $n$-step Bootstrapping](docs/chapter_7_n_step_bootstrapping_sutton_barto_2nd_ed.html)**
  - Bridging one-step TD and full Monte Carlo: $n$-step returns $G_{t:t+n}$, error reduction property, $n$-step Sarsa, off-policy $n$-step learning via importance sampling, the $n$-step Tree Backup algorithm, and $n$-step $Q(\sigma)$.
- [ ] Chapter 8: Planning and Learning with Tabular Methods *(Upcoming)*

### Part II: Approximate Solution Methods
- [ ] Chapter 9: On-policy Prediction with Approximation *(Upcoming)*
- [ ] Chapter 10: On-policy Control with Approximation *(Upcoming)*
- [ ] Chapter 11: Off-policy Methods with Approximation *(Upcoming)*
- [ ] Chapter 12: Eligibility Traces *(Upcoming)*
- [ ] Chapter 13: Policy Gradient Methods *(Upcoming)*