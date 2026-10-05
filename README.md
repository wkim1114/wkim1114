# Hi, I'm Will Kim 👋

M.Eng. student in **Game Development, Design & Innovation** at Duke University with a background in **Data Science, Statistics, and Operations Research** from UNC Chapel Hill.

I'm interested in understanding how complex systems behave and using data and software to analyze, build, and improve them.

**Interested in:** gameplay systems, game AI, and data-driven game design.

- 🎮 Gameplay systems and game AI
- 📈 Simulation and decision-making
- 📊 Data analytics and statistical modeling
- 🧠 Game economy and player behavior
- 🗺️ Geospatial and policy analysis

---

## Education

- **Duke University**: M.Eng., Game Development, Design & Innovation
- **University of North Carolina at Chapel Hill**
  - B.S., Data Science
  - B.S., Statistics
  - Minor, Mathematics

## Skills

- **Languages:** Python, R, C++ (learning)
- **Data & analysis:** multiple linear regression, longitudinal and spatial analysis, data cleaning, API data collection, data visualization, reproducible workflows
- **Game AI & modeling:** opponent modeling, probability estimation, heuristic agents, simulation
- **Learning:** reinforcement learning, backward induction, Unreal Engine, gameplay systems
- **Libraries & tools:** ggplot2, sf, Git/GitHub

---

## Featured Projects

### 🇰🇷 South Korea Fertility Rebound Analysis

Independent data analytics project completed for PLAN 372: Intro to Urban Data Analytics, investigating South Korea's 2025 fertility rebound (provisional total fertility rate of 0.80) across 17 provinces using official government data.

**Tech:** R, ggplot2, sf, KOSIS API

**What I did**
- Programmatically collected data from the Korean Statistical Information Service (KOSIS) API
- Built a reproducible data-cleaning and regression pipeline in R
- Compared base and 9-month lagged multiple linear regression models using standardized (Z-score) variables
- Mapped spatial mismatches between national trends and provincial outcomes using ggplot2 and sf

**Key findings**
- A 9-month lagged model showed a "coefficient flip": areas with rising education costs saw higher fertility rebounds, possibly because those costs signal family-friendly neighborhoods
- National economic factors were not uniformly significant (p > 0.05), pointing to strong local variation
- Argues for targeted, municipal-level interventions over blanket subsidies

[View repository →](https://github.com/wkim1114/rok-fertility-rebound-analysis) · [Presentation (PDF) →](https://github.com/wkim1114/rok-fertility-rebound-analysis/blob/HEAD/Beyond-the-Crisis-Analyzing-South-Koreas-2025-Fertility-Rebound.pdf)

---

### 🎮 Adaptive RPS Agent

Adaptive game AI that learns an opponent's behavior in repeated Rock–Paper–Scissors, exploring opponent modeling, probability-based prediction, and heuristic decision-making.

**Tech:** Python

**What I did**
- Built a probability-based agent that estimates an opponent's move frequencies over a rolling history window (50, 100, or 250 turns) and counters the most likely next move
- Built a point-based heuristic agent that updates move scores every round and explores randomly when appropriate
- Designed both strategies to adapt as the opponent's behavior changes, without complex machine learning models

**Recognition:** 🏆 Best Application of Course Concepts, UNC COMP110 Hackathon

[View repository →](https://github.com/wkim1114/adaptive-rps-agent)

---

### ⭕ TTT-Optimizer: A Strategic Learning Agent for Tic-Tac-Toe

Personal project comparing strategies from a compact strategy tree and backward induction with those learned by a reinforcement learning agent, using Tic-Tac-Toe as the testbed.

**Tech:** Python 3

**Goals**
- Collapse symmetric board states into a strategy tree and score branches with a Branch Expected Value (BEV) approach
- Compare BEV strategies with game-theoretic optimal play from backward induction
- Build a reinforcement learning agent and compare its learned strategies with the optimal ones

**Status:** In progress. Uses concepts from STOR 543: Dynamic Decision Analytics.

[View repository →](https://github.com/wkim1114/ttt-optimizer)

---

### 💰 Game Economy Simulation (work in progress)

Small simulation exploring how currency sources, sinks, and player behavior shape a game economy.

**Tech:** Python

**Status:** Early stage.

[View repository →](https://github.com/wkim1114/game-economy-sim)

---

## Current Focus

In my graduate coursework at Duke, I'm working on:

- Unreal Engine & C++
- Gameplay systems
- Technical portfolio development
- Game economy simulation
- Software engineering fundamentals

---

## Connect

- LinkedIn: [linkedin.com/in/wkim1114](https://www.linkedin.com/in/wkim1114/)
- Email: wk83 at duke.edu

Thanks for stopping by!
