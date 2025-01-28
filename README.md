# Crane Simulation Project

## Table of Contents

- [Introduction](#introduction)
- [Key Components](#key-components)
  - [Initial State](#initial-state)
  - [State Visualisation](#state-visualisation)
  - [Actions and Costs](#actions-and-costs)
- [Functionality](#functionality)
  - [Performing Actions](#performing-actions)
  - [Performing Action Sequences](#performing-action-sequences)
- [Examples](#examples)
  - [Example 1: Move Right](#example-1-move-right)
  - [Example 2: Move Right and Drop](#example-2-move-right-and-drop)
  - [Example 3: Complex Sequence](#example-3-complex-sequence)
- [Applications](#applications)
- [Future Improvements](#future-improvements)

---

## Introduction

The **Crane Simulation Project** models the operation of a crane managing containers in a set of storage bays. The crane can move between bays, pick up containers, and drop them, while tracking the total operational cost. This project provides a foundation for simulating and optimizing warehouse or shipping yard operations.

---

## Key Components

### Initial State

- **`initial_bays`**: Represents storage bays as a list of lists. Each sublist contains the IDs of containers in a specific bay. Example:
  ```python
  initial_bays = [[1, 2], [], [4], []]
