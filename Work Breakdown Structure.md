# Work Breakdown Structure (WBS): MLB Simulation Project

## 1. Project Setup

* 1.1 Create GitHub repository with required folder structure
* 1.2 Set up version control and collaboration protocols
* 1.3 Assign roles (e.g., simulation coder, documentation lead, data collector)

## 2. Data Collection & Preparation

* 2.1 Identify trusted sources for MLB statistics (e.g., Baseball Reference, Fangraphs)
* 2.2 Extract batting averages for top 5 players on each team (Cubs & White Sox)
* 2.3 Extract ERA data for team pitchers
* 2.4 Format and store data in `prepared_data/`
* 2.5 Document data sources and assumptions

## 3. Simulation Model Development

### Level 1: Simple Model

* 3.1 Use average team BA only
* 3.2 Simulate 9-inning game with scoring on hit success
* 3.3 Support multiple-game runs (e.g., 1000 iterations)

### Level 2: Medium Model

* 3.4 Use player-level BA
* 3.5 Implement batting order rotation
* 3.6 Count scoring per hit, rotate lineup

### Level 3: Complex Model

* 3.7 Adjust BA using pitcher ERA
* 3.8 Simulate hit types: single, double, home run
* 3.9 Implement base runner advancement logic

## 4. Output & Results

* 4.1 Store scores and win tallies in `results/`
* 4.2 Visualize score distributions (histograms, boxplots)
* 4.3 Compare team performance across models
* 4.4 Analyze runtime and realism

## 5. Documentation & Project Management

* 5.1 Write functional specs and WBS
* 5.2 Maintain `status_log.md` with progress updates
* 5.3 Log daily activity in `activity_list.md`
* 5.4 Develop project `roadmap.md`
* 5.5 Submit all artifacts and simulation code to GitHub

## 6. AI Documentation

* 6.1 Describe AI-assisted contributions in documentation files
* 6.2 Reflect on how AI improved speed, accuracy, or planning
* 6.3 Include this in final submission for transparency
