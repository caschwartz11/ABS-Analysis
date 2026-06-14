# How Context Influences ABS Challenges
## Overview
Automated Ball-Strike (ABS) was implemented at the beginning of the 2026 MLB season. It allows pitchers, catchers, and batters to challenge balls and called strikes. With a new technology comes a new strategy. Since managers and the bench are not allowed to help the challenger, what influences a player to challenge a call?
## Research Question
Are ABS challenges driven primarily by pitch accuracy or are they influenced by game context?
## Data
  This data comes from [Baseball Savant](https://baseballsavant.mlb.com/) and Statcast. There are over 6,000 challenged pitches and 25,000 pitches in total from the beginning of the season to June 1st. 
  Variables include: pitch location, challenge result, pitch type, count, inning, outs, strike zones, and base runners. 
## Methodology
  Baseball Savant's data classifies the pitches as balls and strikes, and by pitch type. Thus, analysis based on those traits is trivial. However, Savant also classifies pitches as "reasonable," meaning a player could reasonably challenge the pitch. Savant defines a reasonable challenge as a pitch that was called incorrectly, was within 3 inches of the strike zone and would gain at least .3 runs, or the pitch has an expected challenge rate of at least 20%. Unfortunately, the publicly assessiable data does not include labelled reasonable pitches, thus a function was implemented to find the data. 
## Results
### Challenged and Unchallenged Pitches by Location
![Challenge Locations](figures/pos_challenged_unchallenged.png)
This figure compares challenged and unchallenged pitches by location. 

### Confirmed and Overturned Pitches by Location
![Overturned/Confirmed Locations](figures/pos_over_conf.png)
This figure compares challenged pitches by outcome and location. 

### Distance from Zone by Day
![Distance from Zone](figures/dist_from_zone.png)
This figure shows the distance from the edge of the strike zone by day, the daily average. and the overall average.

### Challenge Frequency by Count
![Frequency Count](figures/challenges_by_count.png)
This figure shows the frequency of challenges by count (ball-strike). 

### Challenge Frequency by Runners On
![Frequency Runners](figures/challenges_by_runners.png)
This figure shows the frequency of challenges by runners on base. 

## Key Findings

## Future Work
