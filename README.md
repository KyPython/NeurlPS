# NeurIPS 2024 - Lux AI Season 3


This repository contains the code and tools used to create, train, and evaluate AI agents in the Lux AI environment.
## Table of Contents

## Overview

In **NeurIPS 2024 - Lux AI Season 3**, the challenge revolves around creating agents that excel in a multi-agent 1v1 environment. The agents must perform strategic actions based on a state-of-the-art game setup while also solving biological challenges such as **automated protein complex identification** from **Cryo-ET 3D tomograms**.

### Lux AI 1v1 Game

The Lux AI environment is a competitive 1v1 game where agents learn through interactions, optimizing their decisions for a winning strategy. This project integrates state-of-the-art machine learning techniques, such as **reinforcement learning (RL)** and **meta-learning**, to train an AI agent capable of making intelligent decisions within the environment.

## Model Details

### AI Agent Architecture

The AI agent in this competition uses a combination of **supervised learning**, **reinforcement learning**, and **meta-learning**:

#### Training Setup

- Optimizer: Adam
- Learning Rate: 0.001
- Epochs: 50
- Batch Size: 32
- Loss Function: Cross-entropy
