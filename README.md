## [Multilingual Auxiliary Tasks Training: Bridging the Gap betweenLanguages for Zero-Shot Transfer of Hate Speech Detection Models]()

This is the official repository for the paper. Please due to licence restrictions on the original data set,  we can only provide our strictly comparable cross-lingual hate-speech framework upon requests directed at arij.riabi@inria.fr (Original terms of usage apply).

### Shared tasks used for the Hate speech corpora

| Shared task      | Link                                                     |
|------------------|----------------------------------------------------------|
| Hateval          | https://github.com/msang/hateval                         |
| EVALITA AMi 2018 | https://github.com/MIND-Lab/ami2018                      |
| HaSpeeDe 2018    | https://github.com/msang/haspeede/tree/master/2018       |

### Hate speech detection datasets: Size of full datasets (number of sentences) and new split with comparable data size.

Only the immigrants-es dataset has no blind set.

| Domain-language | train | dev | test | blind |
|-----------------|-------|-----|------|-------|
| immigrants-it   | 2000  | 500 | 1000 | .     |
| immigrants-en   | 4500  | 500 | 1499 | .     |
| immigrants-es   | 1618  | 173 | 800  | .     |
| women-it        | 2500  | 500 | 1000 | .     |
| women-en        | 4500  | 500 | 1472 | .     |
| women-es        | 2882  | 327 | 799  | .     |
| Comparable size | 1618  | 173 | 800  | 1000  |

### Percentage of hateful examples in the train set for the comparable setting

| Language | immigrants | women |
|----------|------------|-------|
| en       | 41.28      | 42.76 |
| es       | 42         | 40.23 |
| it       | 31.33      | 45.42 |

If you make use of this dataset, please cite us:
BibTeX entry and citation info

TO DO ADD
