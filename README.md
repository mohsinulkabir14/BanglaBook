# BᴀɴɢʟᴀBᴏᴏᴋ: A Large-scale Bangla Dataset for Sentiment Analysis from Book Reviews
This repository contains the code, data, and models of the paper titled "BᴀɴɢʟᴀBᴏᴏᴋ: A Large-scale Bangla Dataset for Sentiment Analysis from Book Reviews" published in the ***Findings of the Association for Computational Linguistics: ACL 2023***.

[![arXiv](https://img.shields.io/badge/arXiv-2305.06595-b31b1b.svg)](https://arxiv.org/abs/2305.06595)
[![GoogleScholar](https://img.shields.io/badge/Google%20Scholar-4285F4?style=flat&logo=Google+Scholar&logoColor=white&color=222222&labelColor=4285F4)](https://tinyurl.com/gscholarbanglabook)
[![ResearchGate](https://img.shields.io/badge/ResearchGate-00CCBB?style=flat&logo=ResearchGate&logoColor=white&color=222222&labelColor=00CCBB)](https://www.researchgate.net/publication/370688086_BanglaBook_A_Large-scale_Bangla_Dataset_for_Sentiment_Analysis_from_Book_Reviews)

[![PDF](https://img.shields.io/badge/Paper%20PDF-EF3939?style=flat&logo=adobeacrobatreader&logoColor=white&color=222222&labelColor=ec1c24)](https://arxiv.org/ftp/arxiv/papers/2305/2305.06595.pdf)
[![Slides](https://img.shields.io/badge/Slides%20PDF-EF3939?style=flat&logo=Microsoft+PowerPoint&logoColor=white&color=222222&labelColor=B7472A)](https://drive.google.com/file/d/1-UkYs_Rx11S7qKOfR-6rnO2VDp3W78vQ/view?usp=sharing)
[![Video](https://img.shields.io/badge/Video%20Presentation-4285F4?style=flat&logo=Google+Drive&logoColor=white&color=222222&labelColor=4285F4)](https://drive.google.com/file/d/1i7lnR2y3NdoglmYt31QR1R18mOOYtA76/view?usp=sharing)

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
![dataimage1](images/banglabookgithub1.png)
### Labeling, Translation, and Validation of the Curated Samples
![dataimage2](images/banglabookgithub2.png)

## Results
![resultsimage](images/banglabookgithub3.png)

## Citation
If you find this work useful, please cite our paper:
```
@article{kabir2023banglabook,
  title={BanglaBook: A Large-scale Bangla Dataset for Sentiment Analysis from Book Reviews},
  author={Kabir, Mohsinul and Mahfuz, Obayed Bin and Raiyan, Syed Rifat and Mahmud, Hasan and Hasan, Md Kamrul},
  journal={arXiv preprint arXiv:2305.06595},
  year={2023}
}
```
