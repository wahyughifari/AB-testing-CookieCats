# A/B Testing: Impact of Gate Position on Player Retention – *Cookie Cats*

As a data analyst at a gaming company developing *Cookie Cats*, we conducted an A/B test to evaluate how changing the position of a **gate** (a level-based progression barrier) affects player **retention rates**.

## Background

*Cookie Cats* is a mobile puzzle game where players must complete levels to progress. One key feature of the game is the **gate**, a barrier that forces players to either wait or pay to continue.

By default, the gate is placed at **level 30**. The development team wants to investigate whether moving the gate to **level 40** will improve the number of players returning to the game after 1 and 7 days.

---

## Experiment Objective

To determine whether **delaying the progression barrier** (from level 30 to level 40) increases:

- **Day-1 Retention**: The percentage of players who return to the game one day after installation.
- **Day-7 Retention**: The percentage of players who return to the game seven days after installation.

---

## Experiment Design

| Group      | Description                          |
|------------|--------------------------------------|
| `gate_30`  | Players with the gate at level 30 (Control group) |
| `gate_40`  | Players with the gate at level 40 (Treatment group) |
