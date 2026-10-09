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

## Technologies Used

This project was completed in Python using:

- `pandas` for data cleaning and manipulation
- `seaborn` for visualization
- `matplotlib` for plot formatting

```python
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
