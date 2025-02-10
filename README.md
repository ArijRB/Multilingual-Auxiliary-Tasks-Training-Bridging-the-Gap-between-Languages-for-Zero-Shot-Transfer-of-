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
```
@inproceedings{riabi-etal-2022-taches,
    title = "T{\^a}ches Auxiliaires Multilingues pour le Transfert de Mod{\`e}les de D{\'e}tection de Discours Haineux (Multilingual Auxiliary Tasks for Zero-Shot Cross-Lingual Transfer of Hate Speech Detection)",
    author = "Riabi, Arij  and
      Montariol, Syrielle  and
      Seddah, Djam{\'e}",
    editor = "Est{\`e}ve, Yannick  and
      Jim{\'e}nez, Tania  and
      Parcollet, Titouan  and
      Zanon Boito, Marcely",
    booktitle = "Actes de la 29e Conf{\'e}rence sur le Traitement Automatique des Langues Naturelles. Volume 1 : conf{\'e}rence principale",
    month = "6",
    year = "2022",
    address = "Avignon, France",
    publisher = "ATALA",
    url = "https://aclanthology.org/2022.jeptalnrecital-taln.41/",
    pages = "413--423",
    language = "fra",
    abstract = "La t{\^a}che de d{\'e}tection de contenus haineux est ardue, car elle n{\'e}cessite des connaissances culturelles et contextuelles approfondies ; les connaissances n{\'e}cessaires varient, entre autres, selon la langue du locateur ou la cible du contenu. Or, des donn{\'e}es annot{\'e}es pour des domaines et des langues sp{\'e}cifiques sont souvent absentes ou limit{\'e}es. C`est l{\`a} que les donn{\'e}es dans d`autres langues peuvent {\^e}tre exploit{\'e}es ; mais du fait de ces variations, le transfert cross-lingue est souvent difficile. Dans cet article, nous mettons en {\'e}vidence cette limitation pour plusieurs domaines et langues et montrons l`impact positif de l`apprentissage de t{\^a}ches auxiliaires multilingues - analyse de sentiments, reconnaissance des entit{\'e}s nomm{\'e}es et t{\^a}ches reposant sur des informations morpho-syntaxiques - sur le transfert cross-lingue z{\'e}ro-shot des mod{\`e}les de d{\'e}tection de discours haineux, afin de combler ce foss{\'e} culturel."
}
```
```
@inproceedings{montariol-etal-2022-multilingual,
    title = "Multilingual Auxiliary Tasks Training: Bridging the Gap between Languages for Zero-Shot Transfer of Hate Speech Detection Models",
    author = "Montariol, Syrielle  and
      Riabi, Arij  and
      Seddah, Djam{\'e}",
    editor = "He, Yulan  and
      Ji, Heng  and
      Li, Sujian  and
      Liu, Yang  and
      Chang, Chua-Hui",
    booktitle = "Findings of the Association for Computational Linguistics: AACL-IJCNLP 2022",
    month = nov,
    year = "2022",
    address = "Online only",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2022.findings-aacl.33/",
    doi = "10.18653/v1/2022.findings-aacl.33",
    pages = "347--363",
    abstract = "Zero-shot cross-lingual transfer learning has been shown to be highly challenging for tasks involving a lot of linguistic specificities or when a cultural gap is present between lan- guages, such as in hate speech detection. In this paper, we highlight this limitation for hate speech detection in several domains and languages using strict experimental settings. Then, we propose to train on multilingual auxiliary tasks {--} sentiment analysis, named entity recognition, and tasks relying on syntactic information {--} to improve zero-shot transfer of hate speech detection models across languages. We show how hate speech detection models benefit from a cross-lingual knowledge proxy brought by auxiliary tasks fine-tuning and highlight these tasks' positive impact on bridging the hate speech linguistic and cultural gap between languages."
}
```
