# FIFA 20 Forward Market Value Analysis

## Overview

This project explores how **player position, overall rating, and age relate to market value** among forward players in the FIFA 20 dataset.

The analysis focuses specifically on forward players and separates them into three rating tiers:

- **Bronze:** Overall rating of 64 or below
- **Silver:** Overall rating between 65 and 74
- **Gold:** Overall rating of 75 or above

The project uses boxplots to compare market value across different forward positions and scatterplots to examine how player age relates to market value within each tier.

The main questions are:

1. How does market value differ across forward positions?
2. How does age interact with market value across Bronze, Silver, and Gold players?

---

## Dataset

The project uses the **FIFA 20 player dataset**, which contains information on professional soccer players.

The dataset includes variables such as:

- Player name
- Age
- Nationality
- Club
- Position
- Overall rating
- Potential
- Market value
- Wage
- Pace
- Shooting
- Passing
- Dribbling
- Defending
- Physical attributes

For this project, the main variables used are:

| Variable | Description |
|---|---|
| `age` | Player age |
| `overall` | FIFA overall rating |
| `player_positions` | Listed player positions |
| `value_eur` | Estimated player market value in euros |

---

## Analysis
### Market Value by Forward Position
The first part of the analysis uses boxplots to compare market value distributions across forward positions within each player tier.
Boxplots are useful because they show:
- Median market value
- Middle 50% of player values
- Overall spread
- Differences in the distribution of values between positions
  
Separate boxplots were created for Bronze, Silver, and Gold forwards.

Bronze Players
Bronze forwards show relatively similar market value distributions across the different positions.
The median values for striker, left wing, right wing, and center forward are fairly close to one another.
This suggests that among lower-rated players, the specific forward position does not create a major difference in market value.

Silver Players
The Silver tier begins to show more variation between positions.
Right wings have a somewhat higher median market value and a wider range of values compared with several other forward positions.
However, the distributions are still relatively similar compared with the Gold tier.

Gold Players
The Gold tier shows the largest differences between forward positions.
Center forwards and right wings show particularly wide distributions and higher upper ranges of market value.
Strikers and left wings are somewhat more concentrated.
This suggests that the importance of specific forward positions may become more noticeable among higher-rated players.

### Age vs. Market Value

The second part of the analysis uses scatterplots to explore the relationship between player age and market value.
Each point represents one individual forward player.
Separate scatterplots were created for Bronze, Silver, and Gold players.

Bronze Players
Bronze players appear to reach their highest market values relatively early.
The highest-valued Bronze players are mostly concentrated in their late teens and early twenties.
After the mid-twenties, the upper range of market value begins to decline.
This suggests that younger Bronze players may receive additional market value because of their future development potential.

Silver Players
Silver players show a similar relationship.
Many of the highest-valued Silver players are between approximately 18 and 24 years old.
As players move into their late twenties and thirties, market values generally become lower.
The pattern suggests that age plays an important role in the valuation of mid-level players.

Gold Players
Gold players show a wider range of ages and market values.
Their highest values are generally concentrated throughout their twenties, but elite players can maintain high market values for longer than Bronze or Silver players.
Several Gold players remain highly valuable into their late twenties and early thirties.
However, market values generally begin to decline as players move further into their thirties.
This suggests that elite performance can help players retain market value for longer.

---

## Key Findings

The analysis produced several main observations:
- Market value increases significantly as overall player quality increases.
- Bronze forward positions have relatively similar market value distributions.
- Differences between specific forward positions become more noticeable among Silver and Gold players.
- Gold forwards have much wider market value distributions than Bronze or Silver forwards.
- Younger players generally have greater market value within each tier.
- Bronze and Silver players appear to reach their highest market values earlier.
- Gold players tend to maintain high market value for a longer period.
- Age appears to have a negative relationship with market value after players pass their peak years.
