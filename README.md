# NewsWCL50
NewsWCL50 is the first, open access evaluation dataset for methods seeking to identify bias by word choice and labeling.

The dataset consists (besides some additional files such as the readme you are currently reading) of the following files:

| Name        | Description  | 
| ------------- |-------------|
| `Annotations.csv` | The annotations that we coded during the manual, deductive content analysis. The start and end columns represent the annotation's position as to the original text document in number of tokens. |
| `Codebook.pdf` | The codebook used to conduct the final deductive content analysis. |
| `urls.tsv` | Links each article to its URL so that you can gather the full text if you need to. |

For more information on the dataset, please have a look at our [paper](https://www.gipp.com/wp-content/papercite-data/pdf/hamborg2019a.pdf).

## Gathering the original news articles
NewsWCL50 only contains the annotated parts of the news articles. Due to copyright law, we cannot offer the original articles. However, you can quickly gather the original articles, if you need to work not only with our annotations but also the remainder of the text. In the file [urls.tsv](urls.tsv), each row represents a single article, identified uniquely by its event id, publisher id, and URL. For each article, visit that URL and copy the article's text, including the headline, into a text document. 

## How to cite
Please cite our [paper](https://www.gipp.com/wp-content/papercite-data/pdf/hamborg2019a.pdf) if you are using NewsWCL50:
```
@InProceedings{Hamborg2019a,
  author    = {Hamborg, Felix and Zhukova, Anastasia and Gipp, Bela},
  title     = {Automated Identification of Media Bias by Word Choice and Labeling in News Articles},
  booktitle = {Proceedings of the ACM/IEEE Joint Conference on Digital Libraries (JCDL)},
  year      = {2019},
  month     = {Jun.},
  location  = {Urbana-Champaign, USA}
}
```

You can find more information on this and other news projects on our [website](https://dke.uni-wuppertal.de/en/projects/media-bias-analysis.html).

## License
Licensed under the Attribution-ShareAlike 4.0 International (the "License"); you may not use NewsWCL50 except in compliance with the License. A copy of the License is included in the project, see the file [LICENSE](LICENSE).

Copyright 2018-2019 The NewsWCL50 team
