# Data folder

## Folders

source data:

- **Fixture Download:** https://fixturedownload.com/results/nfl-2024
- **Kaggle NFL scores and betting data:** https://www.kaggle.com/datasets/tobycrabtree/nfl-scores-and-betting-data

### raw

Original, unmodified data after downloading, scraping, etc.

### clean

Cleaned, and modified data after downloading or scraping data.

### final

Data after all cleaning, processing, and analyzing.

---

## Data Dictionary

| Column                  | Data Type | Description                                                                                             |
| ----------------------- | --------- | ------------------------------------------------------------------------------------------------------- |
| **Date**                | `Date`    | The date of the game in `MM/DD/YYYY` format.                                                            |
| **Schedule_Season**     | `Integer` | The year of the season the game is part of.                                                             |
| **Home_Team**           | `String`  | The name of the team playing at home.                                                                   |
| **Score_Home**          | `Integer` | The score of the home team in the game.                                                                 |
| **Away_Team**           | `String`  | The name of the team playing away.                                                                      |
| **Score_Away**          | `Integer` | The score of the away team in the game.                                                                 |
| **Team_Favorite**       | `String`  | The name of the team favored to win the game.                                                           |
| **Spread_Favorite**     | `Float`   | The point spread assigned to the favorite team, indicating how much the favorite is expected to win by. |
| **Over_Under_Line**     | `Float`   | The total points line for the game, combining both teams' scores.                                       |
| **Location**            | `String`  | The name of the stadium or arena the game is played in.                                                 |
| **Weather_Temperature** | `Float`   | The temperature (in Fahrenheit or Celsius) during the game.                                             |
| **Weather_Humidity**    | `Float`   | The humidity percentage at the time of the game.                                                        |
| **Weather_Detail**      | `String`  | A description of the weather conditions (e.g., "Clear skies", "Rainy", "Cloudy", etc.).                 |
| **Result**              | `String`  | The overall result of the game.                                                                         |
| **Spread_Result**       | `Binary`  | The result of the spread bet, with values 1 or 0                                                        |
| **Over_Under_Result**   | `Binary`  | The result of the over/under bet, with values 1 or 0                                                    |
