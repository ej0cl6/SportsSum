## SportsSum

SportsSum is a sports game summarization dataset in Chinese. The goal of SportsSum is to generate sports summaries from live commentaries.

If you find that this dataset is useful in your research, please consider citing our paper.

    @inproceedings{Huang2020sportssum,
        author    = {Kuan-Hao Huang and
                     Chen Li and
                     Kai-Wei Chang},
        title     = {Cost-sensitive label embedding for multi-label classification},
        booktitle = {Proceedings of the 1st Conference of the Asia-Pacific Chapter of the Association for Computational Linguistics (AACL)},
        year      = {2020},
    }
    
### Overview

SportsSum contains live commentaries and news articles of 5,428 soccer games from seven leagues.

| League         |  Number of Games |
|----------------|:----------------:|
| Bundesliga     |  453             |
| CSL            |  1371            |
| Europa         |  143             |
| La Liga        |  713             |
| Ligue 1        |  161             |
| Premier League |  1220            |
| Serie A        |  890             |
| UCL            |  477             |
| All            |  5428            |

### Format

For each game, we have 3 files:
- `live.json` contains live commentary sentences with timeline information as well as scores.
- `news.txt` contains a news article.
- `linesup.json` contains some metadata, such as rosters, starting lineups, and player positions.
