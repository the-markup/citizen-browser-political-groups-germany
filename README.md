# Citizen Browser: Germany’s Far-Right Political Party, the AfD, Is Dominating Facebook This Election
This repository contains data from the story ["Germany’s Far-Right Political Party, the AfD, Is Dominating Facebook This Election"](https://themarkup.org) from from our series, [Citizen Browser](https://themarkup.org/citizen-browser/). Citizen Browser construction and methodology is described in "[How We Built a Facebook Inspector](https://themarkup.org/citizen-browser/2021/01/05/how-we-built-a-facebook-inspector)."

## Data
The `data/` directory contains two csv files with data from the story.

1. `political-page-counts.csv` contains political pages that appeared on our panel's timelines from July 20 through Sept. 16, 2021.
2. `covid-tags.csv` contains counts of posts by poster that were tagged by Facebook for containing COVID-19-related content.
3. `SZ-panel-counts.csv` gives a count of panelists that contributed Facebook captures to this analysis and their self-identified party affiliation.

-----

Data in csv 1 is arranged as follows:
| column           | decription                                                                                |
|:-----------------|:------------------------------------------------------------------------------------------|
| party   | The party assigned to the post based on party keyword found in poster name                           |
| poster       | Name of the Facebook page that published the post  |
| user_count      | The number of unique users who saw posts from this poster  |
| post_count       | The number of posts by the poster that appeared on the panel's Facebook timelines between July 20 and Sept. 16  |


Data in csv 2 is arranged as follows:
| column           | decription                                                                                |
|:-----------------|:------------------------------------------------------------------------------------------|
| party   | The party assigned to the post based on party keyword found in poster name                           |
| poster       | Name of the Facebook page that published the post  |
| flag_count      | The number of posts by the poster that appeared on the panel's Facebook timelines between July 20 and Sept. 16 and were flagged for content related to COVID-19  |

