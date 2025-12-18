
# Australian Open Tennis Championship: A Data Visualization Project

## Project Overview
This project presents a comprehensive visual analysis of the Australian Open Tennis Championship, spanning 120 years of tournament history (1905–2025). Using Tableau, I transformed raw match data into interactive, insightful visualizations that reveal historical trends, national dominance patterns, and the characteristics of elite champions.

The analysis covers:
- **Global tennis power distribution** across nations
- **Gender representation** in championship wins
- **Career longevity and dominance** of top players
- **Match dynamics**, including seeding, win rates, and set-by-set performance
- **Evolution of the tournament** from amateur beginnings to professional era

## Objectives
- To explore and visualize key trends in Australian Open history
- To identify patterns among top champions (5+ titles)
- To analyze match-level statistics and performance metrics
- To demonstrate proficiency in advanced data visualization techniques using Tableau
- To create an engaging, data-driven narrative accessible to tennis enthusiasts and analysts

## Files Included
- `report.pdf`: Full project report (PDF)
- `processed-dataset.xlsx`: Processed dataset with match duration and calculated fields
- `visualizations.twbx`: Packaged Tableau workbook with all visualizations
- `README.md`: Project documentation (this file)

## Tools & Technologies
- **Tableau** - Primary visualization tool
- **Microsoft Excel** - Data preparation and cleaning
- **Python** (optional) - For initial data parsing (if used)
- **ChatGPT & DeepSeek** - Assisted in historical match duration research
- **Markdown & GitHub** - Documentation and portfolio presentation

## Key Visualizations

| Visualization Type | Purpose | Insights Gained |
| :--- | :--- | :--- |
| **Geographic Map** | Show national distribution of champions | Australia’s historical dominance, global spread of winners |
| **Treemap** | Compare champion & runner-up frequencies by nation | Depth of Australian talent vs. isolated champions elsewhere |
| **Word Cloud** | Highlight most frequent champions | Margaret Court & Novak Djokovic as all-time leaders |
| **Scatter Plot** | Analyze career longevity & match dynamics | Modern players have longer, more consistent careers |
| **Parallel Coordinates Plot** | Deconstruct set-by-set match performance | Gender differences in match flow and momentum |
| **Time-Series Charts** | Track seeding trends and win rates over decades | Evolution from unseeded amateur era to structured professional competition |

## Key Findings

### National Dominance
- **Australia** leads with 94 championships, reflecting a long-standing home-court advantage.
- The **United States** follows with 44 titles, showing strong but less concentrated success.
- European success is **dispersed** across multiple nations rather than dominated by one.

### Gender Distribution
- Australian titles are nearly evenly split between men (50) and women (44).
- U.S. women outperform men at the Australian Open (26 vs. 18 titles).
- Some nations show strong gender specialization (e.g., Sweden: men only; Belarus: women only).

### Elite Champions (5+ Titles)
Only 7 players have won 5+ Australian Open titles:
- **Margaret Court** (11) – pre-Open Era dominance
- **Novak Djokovic** (10) – modern-era longevity
- **Serena Williams** (7) – most successful woman in professional era
- **Roy Emerson, Roger Federer, Nancye Wynne Bolton, Daphne Akhurst**

### Career Longevity
- Modern champions (Djokovic, Federer, S. Williams) have career spans of **14–17 years**.
- Historical champions had shorter, more concentrated periods of dominance.

### Match Dynamics
- Higher-seeded players win most finals, but upsets are common.
- **Win rate** negatively correlates with match duration: efficient champions finish faster.
- **First-set performance** strongly predicts match outcome.

## Data Preparation Steps

1. **Data Collection**
    - Match durations were researched using AI assistants (ChatGPT, DeepSeek) and verified manually.
    - Early-era data gaps were acknowledged and handled appropriately.

2. **Data Transformation**
    - Calculated: `Sets Played`, `Games Won`, `Total Games Played`, `Match Win Rate`, `First Set Win Rate`.
    - Normalized set-wise performance metrics for parallel coordinates.
    - Cleaned and binned `Year` for time-series analysis.

3. **Visualization Design**
    - Used consistent color encoding (blue = men, red = women).
    - Applied intentional labeling and annotations to guide interpretation.
    - Designed dashboards to allow interactive exploration.

## Tableau: Advantages & Limitations

| Advantages | Limitations |
| :--- | :--- |
| Rapid prototyping with drag-and-drop interface | Limited customization for complex visual layouts |
| Rich built-in chart types (maps, treemaps, scatter plots) | Data preparation requires external tools for advanced transformations |
| Interactive filtering and dashboard linking | Can become slow with very large datasets |
| Strong community support and resources | Licensing cost for full professional use |

## Skills Demonstrated
- **Data Wrangling** - Cleaning, transforming, and enriching historical data
- **Visual Analytics** - Selecting appropriate chart types for storytelling
- **Statistical Insight** - Identifying correlations, trends, and outliers
- **Dashboard Design** - Creating interactive, user-friendly visual interfaces
- **Report Writing** - Translating data insights into clear, compelling narratives

## Contact
This project was completed as part of the **Advanced Data Visualization and Visual Analytics** course (32146) at the University of Technology Sydney.

> *This project illustrates how data visualization can turn historical records into meaningful insights, revealing not just who won, but how, why, and what it tells us about the evolution of a sport.*
