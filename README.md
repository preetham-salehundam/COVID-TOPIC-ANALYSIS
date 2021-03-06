# COVID-19 Twitter Dataset

Contents of this repository
-----------------------------
This repo contains the datasets used in the study **"Leveraging Natural Language Processing to Mine Issues on Twitter During the COVID-19 Pandemic"**.

The files [Gold_Dataset.tsv](/Gold_Dataset.tsv) contains tweets hand labelled as either **Relevant** or **Irrelevant** to the pandemic by three annotators and [covid-19-dataset-Jan-1-Apr-30.tsv](/covid-19-dataset-Jan-1-Apr-30.tsv) contains all the tweets that are collected from Jan 1st, 2020 to April 30th, 2020 using relevant keywords mentioned in the paper and their relevancy labels ("Relevant" or "Irrelevant") along with the topics identified in our study.

Citation
-----------------

If you use the COVID-19 Dataset, or any of its components please cite the following publication:
https://arxiv.org/pdf/2011.00377.pdf

Bibtex:
@misc{agarwal2020leveraging,
      title={Leveraging Natural Language Processing to Mine Issues on Twitter During the COVID-19 Pandemic}, 
      author={Ankita Agarwal and Preetham Salehundam and Swati Padhee and William L. Romine and Tanvi Banerjee},
      year={2020},
      eprint={2011.00377},
      archivePrefix={arXiv},
      primaryClass={cs.IR}
}





Dataset Information
--------------------

Filename: Gold_Dataset.tsv

| # | Column | Non-Null Count | Dtype |
|--- |------  |-------------- | ----- |
| 0  | Tweet ID |1500 non-null  | int64 |
| 1  | Label   |1500 non-null  | object|

Filename: covid-19-dataset-Jan-1-Apr-30.tsv

| #  | Column                     |  Non-Null Count  | Dtype   |
|--- | ------                     |  --------------  | -----   |
| 0  | Tweet ID                   |  866527 non-null | int64   |
| 1  | Label                      |  866527 non-null | string  |
| 2  | Probability of Irrelevance |  866527 non-null | float64 |
| 3  | Probability of Relevance   |  866527 non-null | float64 |
| 4  | Topic Number               |  689977 non-null | float64 |
| 5  | Dominant Topic             |  689977 non-null | float64 |
| 6  | Topic Contribution         |  689977 non-null | float64 |
| 7  | Topic Keywords             |  689977 non-null | string  |





Details/inquiries
-----------------

For inquiries please contact [Ankita Agarwal](mailto:er.ankitaag@gmail.com) or [Preetham Salehundam](mailto:preetham.salehundam@gmail.com). 