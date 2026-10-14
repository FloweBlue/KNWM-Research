# Knowledge-Neuron World Model (KNWM)

**Independent Research Project | Qinzheng Hu**  
**Research Period:** May 2026 – Present  
**Research Type:** Independent Research  
**Paper:** KNWM: A Knowledge-Neuron Architecture for World Modeling  
**Status:** Under Review at ICLR 2027

---

## Overview

KNWM (Knowledge-Neuron World Model) is a world model I designed and developed to learn, organize, and reuse structured knowledge for reasoning, prediction, complex problem-solving, and autonomous planning. The system focuses on cross-domain scientific knowledge, especially in physics, mathematics, and computer science.

Unlike systems that rely mainly on language models for reasoning, KNWM uses an explicit knowledge-neuron architecture. Learned knowledge is represented in structured, reusable forms and connected in ways that support activation, composition, and execution when solving new problems.

My research asks three central questions:

1. How can AI independently learn and accumulate reusable knowledge?
2. How can learned knowledge be connected and composed to solve complex problems?
3. How can accumulated knowledge support prediction, reasoning, and autonomous planning?

---

## Knowledge-Neuron Architecture

The major contribution of KNWM is its structured knowledge-neuron architecture.

Knowledge is not stored only as raw text or latent vectors. Instead, KNWM organizes learned information into persistent knowledge structures called knowledge neurons. These neurons contain structured information such as:

- identity
- knowledge type
- knowledge provenance
- validation status
- properties
- mathematical expressions
- relationships
- applicability conditions

This design allows knowledge to remain interpretable and reusable.

### Recursive Structure

Knowledge neurons can contain both basic knowledge and references to other neurons. This creates a recursive structure in which simple facts can be combined into more complex scientific or logical knowledge.

For example, basic elements such as mass, distance, time, velocity, and acceleration can be composed into higher-level scientific relationships, causal dependencies, or physical rules.

### Basic and Composite Knowledge

KNWM distinguishes between:

- Basic knowledge: independent semantic elements
- Composite knowledge: combinations of multiple elements or relations

Composite knowledge may represent:

- mathematical relationships
- physical laws
- causal dependencies
- event transitions
- reasoning procedures

This recursive combination is essential for multi-step reasoning and knowledge reuse.

---

## Three Functional Types of Knowledge Neurons

### Scientific Knowledge Neurons

Represent quantitative relationships and executable scientific knowledge such as formulas, laws, numeric relations, and rule conditions. These neurons allow KNWM to directly use prior scientific understanding during computation and prediction.

### Event Knowledge Neurons

Represent actions and events with their preconditions, effects, state transitions, and resource usage. These neurons are particularly useful for planning and simulation.

### Problem Knowledge Neurons

Represent tasks, goals, constraints, subproblems, and target states. These neurons help KNWM understand what must be solved and how to organize the reasoning process.

Together, these three neuron types enable KNWM to reason across scientific knowledge, event simulation, and objective-driven planning.

---

## Overall KNWM Architecture

The system contains two closely connected processes:

1. Knowledge learning and memory
2. Task-driven knowledge use

### Knowledge Learning and Memory

KNWM follows an iterative learning cycle:

Observe → Discover → Validate → Store

- Observe: collect data from the environment and controlled experiments
- Discover: identify candidate relationships or formulas
- Validate: test whether the relationship is reliable and applicable
- Store: organize validated knowledge into neurons and connect related neurons

### Task-Driven Knowledge Use

When a task is received, KNWM follows the process:

Task and Goals → Knowledge Activation → Computation and Simulation → Prediction and Planning

This allows the system to identify the relevant knowledge, activate it, and compose multi-step reasoning structures for solving new problems.

---

## Complex Problem-Solving

KNWM is designed not only to store knowledge, but to apply it to structured, multi-step problems.

The problem-solving process has three major stages:

### Step 1: Identify Facts and Goals

The system identifies known conditions, target variables, and constraints.

### Step 2: Resolve Knowledge Dependencies

It infers which formulas or relationships are required to reach the goal.

### Step 3: Execute the Reasoning Chain

It combines multiple knowledge units into a sequence of calculations or logical steps.

This enables KNWM to construct solutions instead of simply retrieving a memorized answer.

---

## Autonomous Planning

KNWM also supports event-based planning.

The planning process uses scientific knowledge neurons, event knowledge neurons, and problem knowledge neurons together:

1. Define the goal and current state
2. Identify relevant events and their effects
3. Simulate possible outcomes and costs
4. Compare candidate plans
5. Revise plans based on feedback

This allows KNWM to generate plans from structured knowledge rather than relying only on text generation or an LLM to produce a planner from scratch.

---

## Experimental Results

The KNWM work includes several controlled experiments evaluating knowledge learning, compositional reasoning, planning, and prediction.

### Complex Physics Problem-Solving

**Result: 82 / 93**

KNWM solved 82 of 93 selected physics problems under structured evaluation conditions.

### Compositional Reasoning

**Result: 300 / 300**

KNWM successfully completed 300 controlled multi-step knowledge-composition tasks.

### Planning Performance

**Result: 17 vs. 6 optimal plans out of 24 tasks**

With validated knowledge reuse, KNWM produced more optimal plans than the condition without such reuse.

### Scientific Law Learning

**Result: 40 / 40**

KNWM learned 40 scientific relationships in the evaluation setting.

### Trajectory Prediction

**Result: 6,000 / 6,000 checkpoints**

KNWM completed 6,000 prediction checkpoints across 200 evaluated trajectories under supplied motion laws.

These results support the feasibility of the architecture under controlled conditions, while also clarifying the current limitations of the evaluation setup.

---

## Current Research Extensions

I am continuing to extend KNWM in several directions:

### LLM–KNWM Integration

I have developed an initial AGI-oriented system that combines KNWM with an LLM. In this architecture, the LLM handles language input/output while KNWM handles knowledge, memory, reasoning, and planning. The system also includes initial capability-expansion mechanisms that can generate, test, and retain new capabilities.

### 3D Perception

I am improving KNWM's ability to obtain structured information from visual observations, linking 3D perception to the knowledge-neuron architecture.

### Embodied Planning

I am also exploring how KNWM can support embodied planning under dynamic environmental conditions and safety constraints.

These are ongoing research directions rather than claims of fully deployed robotic systems.

---

## Related Research

In addition to KNWM, I have worked on machine learning and cybersecurity research, including:

- Hierarchical Detection of Malicious Command Lines Using Random Forest and Context-Aware LSTM
- Stock Price Prediction Based on Deep Learning

---

## Publication

**Qinzheng Hu**

*KNWM: A Knowledge-Neuron Architecture for World Modeling* — Under Review at ICLR 2027

---

## Research Scope and Limitations

The reported experiments were conducted under controlled conditions, including structured inputs and supplied motion laws. The work is intended to extend KNWM toward more general learning, perception, reasoning, prediction, and autonomous capability development.
