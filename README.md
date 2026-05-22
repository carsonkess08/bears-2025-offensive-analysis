# Chicago Bears 2025 Offensive Analysis

An end-to-end analysis of the Chicago Bears' 2025 offensive performance using
play-by-play data from the nflverse. The project evaluates how efficient the
offense was, where its strengths and weaknesses showed up, and what story the
numbers tell beyond the season-long averages.

## View the Report

**[Click here to view the full interactive report](https://carsonkess08.github.io/bears-2025-offensive-analysis/)**

The report includes interactive charts with hover tooltips for exact values.

## Key Findings

- **Top-tier efficiency.** The Bears ranked 7th of 32 in offensive EPA per play
  (+0.074), placing them firmly in the upper third of the league.
- **A second-half team.** Quarter-by-quarter splits revealed a pattern hidden by
  season averages: the offense was neutral-to-negative in the first half but
  surged after halftime, posting its best efficiency in the fourth quarter
  (+0.168 EPA per play). Slow starts were arguably the offense's biggest missed
  opportunity.
- **Balanced and efficient on early downs.** A 50/50 run-pass split on first down
  paired with strong first-down EPA kept the offense ahead of schedule and
  defenses honest.
- **Above-average on third down.** A 46.6% third-down success rate beat the league
  average of 42.3%.
- **Red zone finishing was the clear weakness.** Ranking 24th of 32 in red zone
  touchdown rate, the Bears struggled to convert scoring chances into touchdowns,
  the most actionable area for improvement.

## Methodology

Data comes from the nflverse `nflreadr` package, covering all 2025 regular season
plays. Analysis is limited to run and pass plays with valid EPA values, excluding
special teams and plays with missing data. EPA (Expected Points Added) measures how
much each play changed the team's expected points given the game situation, and
success rate captures the share of plays that gained enough yardage to be
considered successful for the down and distance. Offensive scoring is isolated to
exclude defensive and special teams points.

## Tools Used

- **R** for all data manipulation and analysis
- **nflreadr** (nflverse) for play-by-play data
- **tidyverse** (dplyr, ggplot2) for data wrangling and visualization
- **plotly** for interactive charts
- **R Markdown** for the final report

## Files

- Bears_Project.html — the rendered interactive report
- Bears-Project.Rmd — the source R Markdown file with all code

## Author

Carson Kessler — Mathematics, University of Iowa
708-625-7110, carsonkess08@gmail.com
