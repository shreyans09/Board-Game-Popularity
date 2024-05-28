# Data

If using an external dataset (that doesn't come in an R package), place data file(s) in this folder.

Then, include metadata about your dataset including information on provenance, codebook, etc.

The codebook for your data file(s) using the following format.

## Games
Note: final games dataset from merging games ~ subcategories ~ themes
| Variable       | Description                                                       |
|:---------------|:------------------------------------------------------------------|
| BBGId          | BoardGameGeek game ID                                             |
| Name           | Name of game                                                      |
| YearPublished  | First year game published                                         |
| GameWeight     | Game difficulty/complexity                                        |
| AvgRating      | Average user rating for game                                      |
| BayesAvgRating | Bayes weighted average for game (x \# of average reviews applied) |
| StdDev         | Standard deviation of Bayes Avg                                   |
| MinPlayers     | Minimum number of players                                         |
| MaxPlayers     | Maximun number of players                                         |
| ComAgeRec      | Community's recommended age minimum                               |
| NumOwned       | Number of users who own this game                                 |
| NumWant        | Number of users who want this game                                |
| NumWish        | Number of users who wishlisted this game                          |
| NumWeightVotes | ? Unknown                                                         |
| MfgPlayTime    | Manufacturer Stated Play Time                                     |
| MfgAgeRec      | Manufacturer Age Recommendation                                   |
| Rank:boardgame | Rank for boardgames overall                                       |
| Theme          | Game theme                                                        |
| Category       | Game subcategory                                                  |
| Cat[...]       | Dummy variables for each category                                 |
| Thm[...]       | Dummy variables for each theme                                    |
