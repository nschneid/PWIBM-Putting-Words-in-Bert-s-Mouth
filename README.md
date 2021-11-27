# Putting Words in BERT's Mouth: Navigating Contextualized Vector Spaces with Pseudowords

This repository contains the code of our paper [Putting Words in BERT's Mouth: Navigating Contextualized Vector Spaces with Pseudowords](https://aclanthology.org/2021.emnlp-main.806/) (EMNLP 2021).

## MaPP Dataset 
The dataset can be found [here](https://github.com/tai314159/PWIBM-Putting-Words-in-Bert-s-Mouth/tree/main/data/csv). 
It is devided to 3 portions (as we describe in our paper). 

## Get Pseudowords 
To get the pseudoword vectors, run the code --> get_pseudowords.py using the data (queries) we provide [here](https://github.com/tai314159/PWIBM-Putting-Words-in-Bert-s-Mouth/blob/main/data/queries/single_target/MaPP_all.txt), or data of the same format.

## Citation
If you found the resources in this repository useful, please cite [our paper](https://aclanthology.org/2021.emnlp-main.806/):

```bibtex
@inproceedings{karidi-etal-2021-putting,
    title = "Putting Words in {BERT}{'}s Mouth: Navigating Contextualized Vector Spaces with Pseudowords",
    author = "Karidi, Taelin  and
      Zhou, Yichu  and
      Schneider, Nathan  and
      Abend, Omri  and
      Srikumar, Vivek",
    booktitle = "Proceedings of the 2021 Conference on Empirical Methods in Natural Language Processing",
    month = nov,
    year = "2021",
    address = "Online and Punta Cana, Dominican Republic",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.emnlp-main.806",
    pages = "10300--10313",
    abstract = "We present a method for exploring regions around individual points in a contextualized vector space (particularly, BERT space), as a way to investigate how these regions correspond to word senses. By inducing a contextualized {``}pseudoword{''} vector as a stand-in for a static embedding in the input layer, and then performing masked prediction of a word in the sentence, we are able to investigate the geometry of the BERT-space in a controlled manner around individual instances. Using our method on a set of carefully constructed sentences targeting highly ambiguous English words, we find substantial regularity in the contextualized space, with regions that correspond to distinct word senses; but between these regions there are occasionally {``}sense voids{''}{---}regions that do not correspond to any intelligible sense.",
}
``` 
