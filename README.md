# RL_notes

Deep research study notes, mathematical derivations, pseudocode, and intuitive diagrams based on Richard S. Sutton and Andrew G. Barto's *Reinforcement Learning: An Introduction* (2nd Edition).

## Live Site
The notes are deployed as a standalone, mobile-responsive visual website via GitHub Pages:  
👉 **[https://yashkhairnar.github.io/RL_notes/](https://yashkhairnar.github.io/RL_notes/)**

---

## Book Structure & Progress (3 / 17 Chapters)

### Part I: Tabular Solution Methods
- [ ] Chapter 1: Introduction *(Upcoming)*
- [ ] Chapter 2: Multi-arm Bandits *(Upcoming)*
- [x] **[Chapter 3: Finite Markov Decision Processes](docs/chapter_3_finite_markov_decision_processes_sutton_barto_2nd_ed.html)**
  - Agent-environment interface, Markov property, return & discounting, value functions, Bellman expectation & optimality equations, backup diagrams.
- [x] **[Chapter 4: Dynamic Programming](docs/chapter_4_dynamic_programming_sutton_barto_2nd_ed.html)**
  - Model-based planning: policy evaluation, policy improvement theorem, policy iteration, value iteration, asynchronous DP, and Generalized Policy Iteration (GPI).
- [x] **[Chapter 5: Monte Carlo Methods](docs/chapter_5_monte_carlo_methods_sutton_barto_2nd_ed.html)**
  - Model-free learning from experience: first-visit vs. every-visit MC, MC with exploring starts, on-policy $\varepsilon$-soft control, off-policy prediction via ordinary/weighted importance sampling, incremental implementation.
- [ ] Chapter 6: Temporal-Difference Learning *(Upcoming)*
- [ ] Chapter 7: $n$-step Bootstrapping *(Upcoming)*
- [ ] Chapter 8: Planning and Learning with Tabular Methods *(Upcoming)*

### Part II: Approximate Solution Methods
- [ ] Chapter 9: On-policy Prediction with Approximation *(Upcoming)*
- [ ] Chapter 10: On-policy Control with Approximation *(Upcoming)*
- [ ] Chapter 11: Off-policy Methods with Approximation *(Upcoming)*
- [ ] Chapter 12: Eligibility Traces *(Upcoming)*
- [ ] Chapter 13: Policy Gradient Methods *(Upcoming)*