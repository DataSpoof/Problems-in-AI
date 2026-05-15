# Planning Problem in AI

The **Planning Problem** in AI refers to the challenge of:

> Determining a sequence of actions that helps an AI achieve a goal.

In simple words:

- AI has a target,
- but must figure out:
  - what steps to take,
  - in what order,
  - while handling constraints and uncertainties.

Planning is a core part of intelligent behavior.

---

# Simple Real-Life Example

Imagine you want to:

# Travel from Delhi to Bangalore

You must plan:

- transport,
- budget,
- timing,
- hotel,
- route,
- food stops.

You cannot randomly act.

You need:
- step-by-step decision making.

AI faces the same challenge.

---

# Main Idea

AI planning involves:

```text
Current State → Actions → Goal State
```

The AI must discover:

> Which sequence of actions transforms the current world into the desired world.

---

# Example

Suppose a robot wants to:

# Make Tea

Steps may include:

1. Boil water
2. Take cup
3. Add tea
4. Pour water
5. Add sugar

Order matters.

Wrong sequence causes failure.

---

# Another Example

Suppose self-driving car must:

- reach destination safely.

It must plan:

- route,
- speed,
- lane changes,
- braking,
- obstacle avoidance.

---

# Why Planning Is Difficult

Because real-world environments contain:

- uncertainty,
- changing conditions,
- limited resources,
- enormous possibilities.

---

# Human vs AI Planning

| Humans | AI Systems |
|---|---|
| Use intuition | Search action spaces |
| Adapt dynamically | Need explicit reasoning |
| Handle uncertainty naturally | Computationally expensive |

---

# Mathematical Intuition

Suppose:

- \(S\) = states,
- \(A\) = actions.

Planning tries to find:

:contentReference[oaicite:0]{index=0}

such that:

:contentReference[oaicite:1]{index=1}

Meaning:

- action sequence transforms:
  - initial state,
  - into goal state.

---

# Components of Planning

# 1. Initial State

Current situation.

---

# Example

Robot is in kitchen.

---

# 2. Goal State

Desired outcome.

---

# Example

Tea is ready.

---

# 3. Actions

Possible operations AI can perform.

---

# Example

- move,
- pick,
- boil,
- pour.

---

# 4. Constraints

Rules or limitations.

---

# Example

- limited battery,
- traffic rules,
- time constraints.

---

# Example in Chess

Goal:
- checkmate opponent.

Planning includes:
- future move prediction,
- strategy evaluation,
- opponent responses.

---

# Example in Navigation Apps

Google Maps plans:

- shortest route,
- fastest route,
- traffic avoidance.

This is AI planning.

---

# Types of Planning Problems

# 1. Classical Planning

Environment assumed:

- fully known,
- deterministic,
- static.

---

# Example

Puzzle solving.

---

# 2. Probabilistic Planning

Actions may fail.

Environment uncertain.

---

# Example

Robot navigation in crowded areas.

---

# 3. Real-Time Planning

AI must plan quickly while environment changes.

---

# Example

Self-driving cars.

---

# 4. Hierarchical Planning

Large tasks broken into smaller subgoals.

---

# Example

“Travel internationally” involves:
- booking,
- passport,
- flights,
- hotels.

---

# Search-Based Planning

Many planning systems use:

# Search Algorithms

to explore action possibilities.

---

# Example Algorithms

| Algorithm | Purpose |
|---|---|
| BFS | Breadth exploration |
| DFS | Deep exploration |
| A* | Optimal path search |
| Dijkstra | Shortest path |
| Minimax | Game planning |

---

# A* Search Formula

```math
f(n)=g(n)+h(n)
```

Where:

- \(g(n)\) = path cost so far,
- \(h(n)\) = estimated remaining cost.

Used heavily in:
- robotics,
- games,
- navigation.

---

# Planning in Robotics

Robot planning includes:

- movement planning,
- object manipulation,
- obstacle avoidance,
- task sequencing.

---

# Example in Warehouses

Warehouse robots plan:

- shortest pickup path,
- collision avoidance,
- delivery sequence.

---

# Planning in LLM Agents

Modern AI agents now perform:

- task planning,
- tool usage planning,
- reasoning chains,
- workflow execution.

---

# Example

AI agent receives:

> “Book a trip.”

Agent may plan:

1. Search flights
2. Compare prices
3. Book hotel
4. Create itinerary

---

# Relation to Reinforcement Learning

Planning and RL are closely related.

| Planning | Reinforcement Learning |
|---|---|
| Uses world model | Learns from experience |
| Explicit reasoning | Trial-and-error learning |

Modern AI often combines both.

---

# Why Planning Is Hard

# 1. Huge Search Space

Possible action sequences grow exponentially.

---

# 2. Uncertainty

Environment changes dynamically.

---

# 3. Partial Information

AI may not know full world state.

---

# 4. Time Constraints

Real-time systems must plan quickly.

---

# Example of Search Explosion

Suppose AI has:

- 10 possible actions,
- for 20 steps.

Possible plans:

```math
10^{20}
```

This becomes computationally enormous.

---

# Planning Under Uncertainty

Real-world AI often plans with probabilities.

---

# Example

Self-driving cars predict:
- pedestrian movement probabilities.

---

# Markov Decision Process (MDP)

A major planning framework.

Defined by:

- states,
- actions,
- rewards,
- transitions.

---

# Bellman Equation

```math
V(s)=\max_a \left[R(s,a)+\gamma \sum_{s'}P(s'|s,a)V(s')\right]
```

Used in:
- RL,
- optimal planning.

---

# Applications

| Domain | Planning Example |
|---|---|
| Robotics | Task sequencing |
| Self-driving cars | Route planning |
| Games | Strategy generation |
| Logistics | Delivery optimization |
| Healthcare | Treatment planning |
| AI Agents | Workflow execution |

---

# Human Analogy

Humans constantly plan:

- careers,
- travel,
- finances,
- conversations,
- daily schedules.

Planning is a core component of intelligence.

---

# Why Planning Matters for AGI

True AGI must:

- reason long-term,
- predict future consequences,
- optimize goals,
- adapt dynamically.

Without planning:
- intelligence remains reactive and limited.

---

# Key Insight

The entire problem can be summarized as:

> “How can AI determine the best sequence of actions needed to achieve a goal?”

That is the essence of the **Planning Problem** in AI.
