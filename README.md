# Traffic Route Guidance (TBRGS)

> A system that predicts traffic and recommends routes across the Boroondara area of Melbourne.

![Type](https://img.shields.io/badge/type-university%20project-blue)

---

## Overview

A system that predicts traffic and recommends routes across the Boroondara area of Melbourne. This repository describes the project at a high level. The source code is not public (see below).

## The Problem

The shortest route is not always the fastest, because traffic changes through the day. A useful route guidance system needs to predict how busy roads will be, then choose routes using those predictions instead of distance alone.

## Why I Built It

A university project combining machine learning and search algorithms, using real traffic data from VicRoads SCATS sensors in Boroondara.

## Key Features

- Predicts traffic from VicRoads SCATS data
- Finds the best route and several alternatives
- Compares three prediction models
- Tkinter GUI for choosing a start and end point
- Written AI ethics report on the impact of the system

## Tools & Technologies

| Area | Tools |
|---|---|
| Languages | Python |
| Frameworks / libraries | Tkinter |
| Data / models | LSTM, GRU, Random Forest; VicRoads SCATS traffic data |
| Algorithms | A* search, Yen's k-shortest paths |

## My Role

- **Project type:** University project at Swinburne University of Technology
- **Duration:** One semester
- **Responsibilities:** [Add what you personally built, and whether this was solo or a group project]

## How It Works

1. Historical SCATS data is cleaned and prepared for the models
2. LSTM, GRU and Random Forest models predict traffic levels
3. Predictions are converted into travel costs on the road network
4. A* finds the best route and Yen's algorithm finds alternatives
5. The Tkinter interface shows the results

## What I Learned

- Preparing real sensor data for machine learning
- Comparing neural networks against a tree-based model
- How A* and k-shortest-path algorithms work in practice
- Thinking about the ethical side of AI in transport

---

## Source Code Availability

The source code for this project is **not public** because it was university coursework and the assessment material cannot be shared publicly.

I'm happy to walk through the project, explain my design decisions, or share more detail on request:

- **Email:** limtisang.shs@gmail.com

---

## Not Included in This Repository

- The assignment brief, marking criteria and solutions
- Datasets that cannot be redistributed
- Any code that would breach the unit's academic integrity rules

<!-- Suggested GitHub description: A system that predicts traffic and recommends routes across the Boroondara area of Melbourne. (README only, source available on request) -->
<!-- Suggested topics: machine-learning,lstm,gru,random-forest,a-star,python,tkinter,university-project -->
