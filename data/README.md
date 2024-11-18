# Data folder

## Folders

source data:

- **Fixture Download:** https://fixturedownload.com/results/nfl-2024
- **Sports Odds History:** https://www.sportsoddshistory.com/nfl-game-season/?y=2024

### raw

Original, unmodified data after downloading, scraping, etc.

### final

Data after all cleaning, processing, and analyzing.

---

## Data Dictionary

| Column                | Data Type | Description                                                                                    |
| --------------------- | --------- | ---------------------------------------------------------------------------------------------- |
| **Date**              | `Date`    | The date of the game in `YYYY-MM-DD` format.                                                   |
| **Favorite**          | `String`  | The name of the team favored to win the game.                                                  |
| **Underdog**          | `String`  | The name of the team expected to lose the game.                                                |
| **Score**             | `String`  | The final score of the game, formatted as "Favorite_Score-Underdog_Score".                     |
| **Moneyline_Result**  | `String`  | Indicates whether the favorite or underdog won, with values `Favorite`, `Underdog`, or `Push`. |
| **Spread**            | `Float`   | The point spread assigned to the game, indicating how much the favorite is expected to win by. |
| **Spread_Result**     | `String`  | The result of the spread bet, with values `Cover`, `Not Cover`, or `Push`.                     |
| **Over_Under**        | `Float`   | The total points line for the game, combining both teams' scores.                              |
| **Over_Under_Result** | `String`  | The result of the over/under bet, with values `Over`, `Under`, or `Push`.                      |
