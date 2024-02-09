# Roulette Betting Strategy Simulation

## Overview

This Python script simulates a betting strategy for playing roulette. The strategy involves doubling the bet after a loss and resetting to $1 after a win. The primary focus of this simulation is to demonstrate the concept of a random walk and its application in a stochastic process.

## Random Walk and Stochastic Process

### Random Walk

In probability theory, a **random walk** is a mathematical model that describes a path consisting of a succession of random steps. In this simulation, the random walk represents the evolution of the player's total money over a series of roulette rounds.

### Stochastic Process

A **stochastic process** is a collection of random variables representing the evolution of a system over time. In our case, the total money after each roulette round forms a stochastic process. The randomness in the outcomes of each round, combined with the betting strategy, contributes to the stochastic nature of the process.

## Betting Strategy

The betting strategy employed in this simulation is as follows:

- After a loss, double the bet.
- After a win, reset the bet to $1.

This strategy introduces a dynamic element to the random walk, influencing the size of the steps taken in each round based on the previous outcomes.

## Running the Simulation

To run the simulation, execute the `roulette_simulation.py` script:

```bash
python roulette_simulation.py
