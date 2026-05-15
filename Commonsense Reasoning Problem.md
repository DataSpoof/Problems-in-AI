# Commonsense Reasoning Problem in AI

The **Commonsense Reasoning Problem** in AI refers to the challenge of:

> Making AI understand and reason about the world using everyday human common sense.

In simple words:

- humans naturally understand obvious things,
- but AI systems often struggle with them.

Even advanced AI can fail at very simple real-world reasoning tasks.

---

# Simple Real-Life Example

Suppose someone says:

> “John put ice cream in the sun.”

Humans instantly understand:

- the ice cream will melt.

Nobody needs to explain:
- heat melts ice cream.

But AI may fail unless it has explicitly learned this relationship.

This is the commonsense reasoning problem.

---

# Main Idea

Humans possess massive amounts of implicit knowledge about:

- physics,
- time,
- space,
- emotions,
- social behavior,
- cause and effect.

Most of this knowledge is never explicitly written down.

AI systems struggle because:

> Common sense is rarely fully stated in data.

---

# Example

Question:

> “Can an elephant fit inside a refrigerator?”

Humans instantly know:

- no,
- because elephants are too large.

AI may:
- overanalyze,
- generate strange reasoning,
- fail unexpectedly.

---

# Another Example

Sentence:

> “The trophy didn’t fit into the suitcase because it was too big.”

What was too big?

Humans know:
- trophy.

AI may struggle because:
- “it” is ambiguous.

This requires common sense reasoning.

---

# Why Commonsense Is Difficult for AI

Because the real world contains:

- billions of implicit assumptions,
- physical laws,
- social norms,
- contextual rules.

Humans learn these naturally through life experience.

AI mostly learns from:
- text,
- data patterns,
- probabilities.

---

# Human Commonsense Examples

Humans naturally know:

- fire is hot,
- water is wet,
- dropped objects fall,
- glass can break,
- people get tired,
- food can spoil.

But teaching all such knowledge explicitly to AI is extremely hard.

---

# Historical Background

Commonsense reasoning has been a major AI challenge since the beginning of AI research.

Researchers realized:

> Intelligence is not just logic or calculations.

True intelligence requires:
- understanding ordinary everyday reality.

---

# Symbolic AI Approach

Early AI systems tried using:

- rules,
- logic,
- knowledge bases.

Example:

```text
IF object is glass AND object falls
THEN object may break
```

But real life has:
- countless exceptions,
- enormous complexity.

Rule-based systems became difficult to scale.

---

# Why Data Alone Is Not Enough

Even huge datasets may not capture:

- unstated assumptions,
- physical intuition,
- social understanding.

Humans often omit obvious facts because:
- everyone already knows them.

---

# Example in Language Understanding

Sentence:

> “Sarah dropped the vase. It shattered.”

Humans infer:
- vase broke.

Because we understand:
- glass objects are fragile.

AI may struggle without commonsense grounding.

---

# Commonsense vs Memorization

| Memorization | Commonsense Reasoning |
|---|---|
| Learns patterns | Understands situations |
| Surface-level matching | Deep contextual inference |
| Statistical correlation | Real-world understanding |

---

# Commonsense Categories

# 1. Physical Commonsense

Understanding:
- gravity,
- motion,
- size,
- temperature.

Example:
- heavy objects are hard to lift.

---

# 2. Social Commonsense

Understanding:
- emotions,
- intentions,
- etiquette.

Example:
- insulting people causes anger.

---

# 3. Temporal Commonsense

Understanding time relationships.

Example:
- breakfast happens before dinner.

---

# 4. Spatial Commonsense

Understanding space and geometry.

Example:
- cars do not fit inside pockets.

---

# 5. Causal Commonsense

Understanding cause and effect.

Example:
- cutting power turns lights off.

---

# Mathematical Perspective

Traditional AI often optimizes probabilities:

:contentReference[oaicite:0]{index=0}

But commonsense requires:

- world models,
- causal reasoning,
- physical understanding.

Not just probabilities.

---

# Commonsense Failures in AI

AI may fail on questions like:

> “If I put a book on a table, where is the book?”

Humans:
- on the table.

AI sometimes:
- gives strange or overly complicated answers.

---

# Example in Robotics

Suppose robot hears:

> “Bring me the hot coffee carefully.”

Humans understand:
- hot liquids can spill,
- careful movement is needed.

Robot must learn:
- physical safety,
- motion constraints,
- human expectations.

---

# Commonsense in Self-Driving Cars

Cars need commonsense such as:

- pedestrians may cross unexpectedly,
- children behave unpredictably,
- rain makes roads slippery.

These are not just mathematical calculations.

---

# Why Commonsense Is Important for AGI

Without commonsense:

AI may:
- make absurd decisions,
- fail in real-world environments,
- misunderstand simple situations.

Commonsense is considered essential for:
- AGI,
- robust reasoning,
- safe autonomous systems.

---

# Modern AI Approaches

Researchers are improving commonsense using:

- Large Language Models,
- multimodal learning,
- world models,
- reinforcement learning,
- knowledge graphs.

---

# Knowledge Graph Example

AI stores relationships like:

```text
Bird → can fly
Fish → lives in water
Fire → produces heat
```

This improves reasoning.

---

# Multimodal AI

Combining:

- text,
- images,
- video,
- audio,
- robotics.

helps AI learn real-world understanding.

---

# Commonsense Benchmarks

Researchers test AI using benchmarks like:

- CommonsenseQA
- Winograd Schema Challenge
- HellaSwag

These measure:
- contextual reasoning ability.

---

# Example: Winograd Schema

Sentence:

> “The city council refused the demonstrators a permit because they feared violence.”

Who feared violence?

Humans infer:
- city council.

AI often struggles.

---

# Human Analogy

A child learns commonsense through:

- seeing,
- touching,
- social interaction,
- trial and error,
- daily life experiences.

Humans build internal world understanding naturally.

---

# Applications

| Domain | Commonsense Requirement |
|---|---|
| Robotics | Safe interaction with world |
| Chatbots | Natural conversation |
| Self-driving cars | Real-world judgment |
| Healthcare AI | Human-context understanding |
| Personal assistants | Everyday reasoning |
| AI agents | Goal-oriented decision making |

---

# Current Challenges

Even advanced AI systems still struggle with:

- deep causal reasoning,
- physical intuition,
- long-term contextual understanding,
- social understanding.

---

# Key Insight

The entire problem can be summarized as:

> “How can AI understand the everyday knowledge and reasoning that humans naturally take for granted?”

That is the essence of the **Commonsense Reasoning Problem** in AI.
