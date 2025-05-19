# Functional Specifications: MLB Simulation Project

## Project Title

**Simulating MLB Game Outcomes: White Sox vs Cubs (Three-Tiered Modeling)**

## Project Summary

This project uses Monte Carlo simulation techniques to model baseball game outcomes between the Chicago White Sox and the Chicago Cubs using three levels of complexity. The goal is to evaluate team performance under varying assumptions and modeling detail, from team-level averages to player-level interactions with opposing pitchers.

## Goals and Objectives

* Implement three simulation models of increasing complexity:

  * Level 1: Team-level batting average model
  * Level 2: Player-level batting average with lineup rotation
  * Level 3: Player-level modeling with pitcher adjustment and hit types
* Compare team outcomes across simulations (scores, win rates)
* Assess model performance and realism

## User Stories

* **As a baseball analyst**, I want to simulate team matchups so I can predict likely outcomes.
* **As a data scientist**, I want to model realistic gameplay interactions using player stats so that I can perform statistical analysis.
* **As an AI-assisted team**, I want to document the simulation logic and code so the project is reproducible and transparent.

## Functional Requirements

* [ ] Code for each model level must be contained in `functional_code/` and callable with parameters
* [ ] Models must support running multiple simulations (e.g., 1000 games)
* [ ] Use real batting average (BA) and ERA data from the most recent season
* [ ] Save results (average score, win rate) to `results/`
* [ ] Log AI-assisted contributions in documentation

## Non-functional Requirements

* [ ] Code should be written in clean Python with comments
* [ ] Outputs must be reproducible with a fixed seed
* [ ] Simulation runtime for each model should complete within 1 minute for 1000 games

## Acceptance Criteria

* ✔ Three simulation models are implemented and tested
* ✔ Real-world 2025 data is used in each model
* ✔ Results are saved and compared in plots or tables
* ✔ All documentation artifacts are complete and committed to GitHub
