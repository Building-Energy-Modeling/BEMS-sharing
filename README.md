# BEMS-sharing

> The official website and resource-sharing hub of the IEEE PES Task Force on Building Energy Modeling for Flexible Scheduling.

## Overview

BEMS-sharing is an open and collaborative platform for **Building Energy Management System (BEMS)** research and resource sharing.  
It aims to collect and organize building energy modeling methods, datasets, intelligent agent tools, and technical reports to support integrated research on building-side energy modeling and power scheduling optimization.

## Background

As buildings become increasingly coupled with power systems and renewable energy resources, it is becoming essential to connect building information models (BIM), simulation-based models, data-driven approaches, and power scheduling algorithms.  
This project focuses on key challenges in:

- Building energy modeling and prediction
- Flexible scheduling and optimization of building loads
- Bridging the semantic gap between BIM and scheduling algorithms
- Visualization of building-scale and city-scale energy analysis
- Collaborative modeling with physical models, machine learning, and large language model (LLM) agents

## Core Features

This website and its related repository provide the following content:

- **Building modeling methods**  
  Covering simulation-driven, data-driven, and physics-informed approaches.
- **Building datasets**  
  Data resources for modeling, simulation, and validation.
- **LLM/Agent-based interactive modeling support**  
  Human-AI collaborative modeling workflows powered by large language models.
- **Visualization**  
  Supports results presentation at both building and city scales.
- **Flexible scheduling applications**  
  Applicable to MPC, RL, and other optimization/control methods for building energy systems.
- **Technical reports and documentation**  
  Includes content related to EnergyPlus, PVsyst, ML, NN, RC models, PINNs, transfer learning, and more.

## Use Cases

This repository is suitable for:

- Building energy modeling and simulation research
- Flexible load and demand response studies
- Integrated BIM and energy system analysis
- Exploring agent-assisted modeling workflows
- City-scale building energy data visualization
- Academic project presentation, result archiving, and resource sharing

## Suggested Repository Structure

Based on the current website content, the repository may be organized as follows:

```text
.
├── README.md
├── _config.yml
├── index.md / pages/
├── assets/
│   ├── images/
│   └── figures/
├── docs/
│   ├── introduction.md
│   ├── reports/
│   └── references/
├── modeling-dataset/    # Modeling-related resources
├── simulation/          # Datasets / simulation resources
├── agent/               # LLM agent-related content
└── examples/            # Demos and examples
