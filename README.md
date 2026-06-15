# UEFA Champions League Finals Shot Analysis (2009–2019)

## Overview

This project analyzes shot data from UEFA Champions League Finals between 2009 and 2019 using the StatsBomb Open Data dataset.

The objective was to explore shooting patterns, player performance, and expected goals (xG) in some of the most important matches in world football. The analysis combines data processing, statistical analysis, and data visualization using Python.


## Dataset

Source: StatsBomb Open Data

Competition:

* UEFA Champions League

Seasons:

* 2008/09 to 2018/19 Finals

Data includes:

* Shot locations
* Expected Goals (xG)
* Shot outcomes
* Player information
* Match information

Penalty shootout events were excluded from the analysis.


## Key Questions

* Which players overperformed their expected goals?
* Which players underperformed their expected goals?
* Where are most shots taken from in Champions League Finals?
* How do Lionel Messi and Cristiano Ronaldo compare in terms of shot quality and finishing?
* How are shots distributed across different shooting zones?
  

## Methodology

### Data Processing

The event data from each final was loaded and filtered to include only shot events.

For each shot, the following variables were extracted:

* Match ID
* Player Name
* Shot Location (x, y)
* Expected Goals (xG)
* Shot Outcome

Players with fewer than five shots across all finals were excluded from player-level comparisons to reduce small-sample bias.


### Shot Zones

Shots were classified into three zones:

1. Six-Yard Box
2. Penalty Box
3. Outside Penalty Box

This allowed analysis of where shots were taken and how goal-scoring probability varied by location.


## Visualizations

The project generates:

### Messi vs Ronaldo Shot Map

Comparison of:

* Shot locations
* Goal locations
* Shot quality (xG)
* Total goals scored

### xG Overperformers

Players who scored more goals than expected based on xG.

Metric:

Goals − xG

### xG Underperformers

Players who scored fewer goals than expected based on xG.

Metric:

Goals − xG

### Shot Zone Distribution

Percentage of shots taken from:

* Six-yard box
* Penalty box
* Outside penalty box

### Shot Zone Map

Visualization of all shots grouped by shooting zone.


## Technologies Used

* Python
* Pandas
* Matplotlib
* mplsoccer


## Key Findings

* Most shots in Champions League Finals originate from inside the penalty area.
* Finishing performance varies significantly even among elite players.
* Expected Goals provides a useful benchmark for evaluating finishing efficiency.
* Shot location strongly influences scoring probability.


## Future Improvements

* Include additional Champions League seasons
* Analyze team-level shooting performance
* Compare different competitions
* Build interactive visualizations using Plotly
* Investigate trends in xG over time

