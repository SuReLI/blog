## Reachability Graph Learning

We are pleased to announce the publication of the research paper titled "Learning State Reachability as a Graph in Translation Invariant Goal-based Reinforcement Learning Tasks" in the TMLR journal.  
This work was co-authored by Hedwin Bonnavaud, Alexandre Albore (ONERA Toulouse), and Emmanuel Rachelson.

TL;DR: We train a control goal-conditioned policy and use it with a graph for global planning. The main contribution is the exploitation of the environment dynamics to perform zero-shot RL with the control policy.

### Abstract

Deep Reinforcement Learning proved efficient at learning universal control policies when
the goal state is close enough to the starting state, or when the value function features few
discontinuities. But reaching goals that require long action sequences in complex environ-
ments remains difficult. Drawing inspiration from the cognitive process which reuses learned
atomic skills in a global planning procedure, we propose an algorithm which encodes reach-
ability between abstract goals as a graph, and produces plans in this goal space. Transitions
between goals rely on the exploitation of a learned policy which enjoys a property we call
translation invariant local optimality, which encodes the intuition that goal-reaching skills
can be reused throughout the state space. Overall, our contribution permits solving large
and difficult navigation tasks, outperforming related methods from the literature.

### Key Findings

- We propose a generic framework linking goal spaces and state spaces for goal-reaching policy opti-
mization.
- We formalize the notion of re-usability of a goal-reaching policy throughout the state space as one
of translation invariance.
- We propose a complete graph-based model learning method, which relies on planning in the goal
space, and chains local application of translation invariant goal-reaching policies. By combining
planning and RL, this method permits solving tasks over long horizons, a common pitfall for classical
RL methods.
  
### Publication Details

* **Title**: Learning State Reachability as a Graph in Translation Invariant Goal-based Reinforcement Learning Tasks
* **Journal**: Transactions on Machine Learning Research
* **Link to Publication**: Read the full paper [here](https://openreview.net/pdf?id=PkHkPQMTxg)
