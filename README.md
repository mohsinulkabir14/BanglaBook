# BᴀɴɢʟᴀBᴏᴏᴋ: A Large-scale Bangla Dataset for Sentiment Analysis from Book Reviews
This repository contains the code, data, and models of the paper titled "BᴀɴɢʟᴀBᴏᴏᴋ: A Large-scale Bangla Dataset for Sentiment Analysis from Book Reviews" published in the ***Findings of the Association for Computational Linguistics: ACL 2023***.

[![arXiv](https://img.shields.io/badge/arXiv-2305.06595-b31b1b.svg?logo=arxiv)](https://arxiv.org/abs/2305.06595)
[![anthology](https://img.shields.io/badge/ACL%20Anthology-2023.findings--acl.80-EE161F?logo=data:image/png;base64,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&style=flat")](https://aclanthology.org/2023.findings-acl.80/)
[![GoogleScholar](https://img.shields.io/badge/Google%20Scholar-4285F4?style=flat&logo=Google+Scholar&logoColor=white&color=gray&labelColor=4285F4)](https://tinyurl.com/gscholarbanglabook)
[![ResearchGate](https://img.shields.io/badge/ResearchGate-00CCBB?style=flat&logo=ResearchGate&logoColor=white&color=gray&labelColor=00CCBB)](https://www.researchgate.net/publication/370688086_BanglaBook_A_Large-scale_Bangla_Dataset_for_Sentiment_Analysis_from_Book_Reviews)
[![HuggingFace](https://img.shields.io/badge/Hugging%20Face-yellow?style=flat&logo=HuggingFace&logoColor=black&color=gray&labelColor=yellow)](https://huggingface.co/datasets/Starscream-11813/BanglaBook)

[![PDF](https://img.shields.io/badge/Paper%20PDF-EF3939?style=flat&logo=adobeacrobatreader&logoColor=white&color=gray&labelColor=ec1c24)](https://aclanthology.org/2023.findings-acl.80.pdf)
[![Slides](https://img.shields.io/badge/Slides%20PDF-EF3939?style=flat&logo=airplayvideo&logoColor=white&color=gray&labelColor=B7472A)](https://drive.google.com/file/d/1-UkYs_Rx11S7qKOfR-6rnO2VDp3W78vQ/view?usp=sharing)
[![Video](https://img.shields.io/badge/Video%20Presentation-4285F4?style=flat&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCA1NzYgNTEyIj48IS0tIUZvbnQgQXdlc29tZSBGcmVlIDYuNS4yIGJ5IEBmb250YXdlc29tZSAtIGh0dHBzOi8vZm9udGF3ZXNvbWUuY29tIExpY2Vuc2UgLSBodHRwczovL2ZvbnRhd2Vzb21lLmNvbS9saWNlbnNlL2ZyZWUgQ29weXJpZ2h0IDIwMjQgRm9udGljb25zLCBJbmMuLS0+PHBhdGggZmlsbD0iI2ZmZmZmZiIgZD0iTTAgMTI4QzAgOTIuNyAyOC43IDY0IDY0IDY0SDMyMGMzNS4zIDAgNjQgMjguNyA2NCA2NFYzODRjMCAzNS4zLTI4LjcgNjQtNjQgNjRINjRjLTM1LjMgMC02NC0yOC43LTY0LTY0VjEyOHpNNTU5LjEgOTkuOGMxMC40IDUuNiAxNi45IDE2LjQgMTYuOSAyOC4yVjM4NGMwIDExLjgtNi41IDIyLjYtMTYuOSAyOC4ycy0yMyA1LTMyLjktMS42bC05Ni02NEw0MTYgMzM3LjFWMzIwIDE5MiAxNzQuOWwxNC4yLTkuNSA5Ni02NGM5LjgtNi41IDIyLjQtNy4yIDMyLjktMS42eiIvPjwvc3ZnPg==&logoColor=white&color=gray&labelColor=B197FC)](https://aclanthology.org/2023.findings-acl.80.mp4)

**License:** Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International

[![license](https://arxiv.org/icons/licenses/by-nc-sa-4.0.png)](http://creativecommons.org/licenses/by-nc-sa/4.0/)

## Data Format
Each row consists of a book review sample. The table below describes what each column signifies.

Column Title | Description
------------ | -------------
`id` | The unique identification number of the sample
`Book_Name` | The title of the book that has been evaluated by the review
`Writer_Name` | The name of the book's author
`Category` | The genre to which the book belongs
`Rating` | A numerical value $`r`$ such that $`1\leq r \leq 5`$<br>A score reflecting the reviewer's subjective assessment of the book's quality
`Review` | The review text written by the reviewer
`Site` | The name of the online bookshop
`sentiment` | The conveyed sentiment and class label of the review<br>For a review sample $`i`$ with rating $`r_i`$, the sentiment label $`S_i`$ is,<br>$`S_i =\begin{cases}Negative, & \text{if $r_i \leq 2$}\\Neutral, & \text{if $r_i = 3$}\\Positive, & \text{if $r_i \geq 4$}\end{cases}`$
`label` | The numerical representation of the sentiment label<br>For a review sample $`i`$ with sentiment label $`S_i`$, the numerical label is,<br>$`label_i =\begin{cases}0, & \text{if $S_i = Negative$}\\1, & \text{if $S_i = Neutral$}\\2, & \text{if $S_i = Positive$}\end{cases}`$

## Data Construction
### Data Collection Process
For the data collection and preparation process of the BᴀɴɢʟᴀBᴏᴏᴋ dataset, we first compile a list of URLs for authors from online bookstores. From there, we procure URLs for the books. We meticulously scrape information such as book titles, author names, book categories, review texts, reviewer names, review dates, and ratings by utilizing these book URLs. 
![dataimage1](images/banglabookgithub1.png)
### Labeling, Translation, and Validation of the Curated Samples
If a review does not have a rating, we deem it unannotated. Reviews with a rating of 1 or 2 are classified as negative, a rating of 3 is considered neutral, and a rating of 4 or 5 is classified as positive. After discarding the unannotated reviews, we curate a final dataset of 158,065 annotated reviews. Of these, 89,371 are written entirely in Bangla. The remaining 68,694 reviews were written in Romanized Bangla, English, or a mix of languages. They are translated into Bangla with Google Translator and a custom Python program using the `googletrans` library. The translations are subsequently subjected to manual review and scrutiny to confirm their accuracy.
![dataimage2](images/banglabookgithub2.png)

## Results
![resultsimage](images/banglabookgithub3.png)

## Citation
If you find this work useful, please cite our paper:
```bib
@inproceedings{kabir-etal-2023-banglabook,
    title = "{B}angla{B}ook: A Large-scale {B}angla Dataset for Sentiment Analysis from Book Reviews",
    author = "Kabir, Mohsinul  and
      Bin Mahfuz, Obayed  and
      Raiyan, Syed Rifat  and
      Mahmud, Hasan  and
      Hasan, Md Kamrul",
    booktitle = "Findings of the Association for Computational Linguistics: ACL 2023",
    month = jul,
    year = "2023",
    address = "Toronto, Canada",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.findings-acl.80",
    pages = "1237--1247",
    abstract = "The analysis of consumer sentiment, as expressed through reviews, can provide a wealth of insight regarding the quality of a product. While the study of sentiment analysis has been widely explored in many popular languages, relatively less attention has been given to the Bangla language, mostly due to a lack of relevant data and cross-domain adaptability. To address this limitation, we present BanglaBook, a large-scale dataset of Bangla book reviews consisting of 158,065 samples classified into three broad categories: positive, negative, and neutral. We provide a detailed statistical analysis of the dataset and employ a range of machine learning models to establish baselines including SVM, LSTM, and Bangla-BERT. Our findings demonstrate a substantial performance advantage of pre-trained models over models that rely on manually crafted features, emphasizing the necessity for additional training resources in this domain. Additionally, we conduct an in-depth error analysis by examining sentiment unigrams, which may provide insight into common classification errors in under-resourced languages like Bangla. Our codes and data are publicly available at https://github.com/mohsinulkabir14/BanglaBook.",
}
```
