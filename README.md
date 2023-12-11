# id-vaccines-tweets

Dataset containing tweets about COVID-19 vaccines with manually labelled information about whether they are a subjective tweet and their sentiment polarity. Tweets are from 20-27 June 2021 and 15-22 July 2021.

`id_vaccine_tweets.csv` contains 4183 instances with 4 columns: `norm`, `formal`, `subjektif`, `posneg`. Description of each column:

| Column  | Description |
| ------------- | ------------- |
| `norm` | normalized tweets (removed mentions, links, etc) raw tweets excluded to remove potential PIDs |
| `formal` | formalized form of the `norm` column using a Colloquial Indonesian Lexicon (Salsabila et al., [2018](https://ieeexplore.ieee.org/abstract/document/8629151])) |
| `subjektif` | Indicator whether a tweet is subjective. 0 is not subjective, 1 is subjective |
| `posneg` | tweet sentiment polarity. -1 is negative, 0 is neutral, 1 is positive|

Report is available in `id_covid19_vaccines_sent_analysis.pdf`

### Authors:
- Ryandito Diandaru 13519157@std.stei.itb.ac.id
- Muhammad Fawwaz Naabigh 13519206@std.stei.itb.ac.id
- Randy Zakya Suchrady 13519061@std.stei.itb.ac.id