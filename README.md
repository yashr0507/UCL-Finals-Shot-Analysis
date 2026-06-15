# UEFA Champions League Finals Shot Analysis (2009–2019)

## Overview

This project analyzes shot data from UEFA Champions League Finals between 2009 and 2019 using StatsBomb Open Data. The goal was to explore shooting efficiency, expected goals (xG), player overperformance relative to xG, and shot location patterns in football's biggest club match.

## Dataset

* Competition: UEFA Champions League Finals
* Seasons: 2009–2019
* Total Shots: 321
* Total Goals: 40
* Data Source: StatsBomb Open Data

## Objectives

* Analyze shot distribution across different areas of the pitch.
* Compare goals scored against expected goals (xG).
* Identify the biggest xG overperformers and underperformers.
* Compare the shooting profiles of Lionel Messi and Cristiano Ronaldo in UCL Finals.
* Visualize spatial shooting patterns using football pitch maps.

## Key Findings

* Most shots were taken from inside the penalty area.
* Gareth Bale recorded the highest positive 'Goals − x' value among players with at least five shots.
* Arjen Robben recorded the largest negative 'Goals − xG' value among players with at least five shots.
* Messi and Ronaldo showed different shot selection patterns despite producing similar levels of shot quality.

## Visualizations

### Messi vs Ronaldo Shot Map

Comparison of shot locations, goals, and xG in Champions League Finals.

### xG Overperformers

Players who scored more goals than expected based on shot quality.

### xG Underperformers

Players who scored fewer goals than expected based on shot quality.

### Shot Zone Distribution

Percentage of shots taken from:

* 6-yard box
* Penalty box
* Outside penalty box

### Shot Location Map by Zone

Spatial visualization of all shots categorized by shooting zone.

## Methodology

Expected Goals (xG) values were provided directly by StatsBomb.

For player-level xG comparisons, only players with at least five shots were included to reduce small-sample bias.

Shot locations were grouped into three zones:

* 6-yard box
* Penalty box
* Outside penalty box

## Tools Used

* Python
* Pandas
* Matplotlib
* mplsoccer
* StatsBomb Open Data

## Future Improvements

* Shot angle analysis
* Team-level comparisons
* Season-by-season xG trends
* Pass network analysis
* Shot assist analysis
