# ChID-Dataset
The ChID Dataset for paper **[ChID: A Large-scale Chinese IDiom Dataset for Cloze Test](https://arxiv.org/abs/1906.01265)**

If you have any question about the dataset, please get in touch with me zhengchj16@gmail.com or zcj16@mails.tsinghua.edu.cn!

If your research is related to or based on our ChID dataset (or the version adapted for the competition), please kindly cite it:

```
@article{zheng2019chid,
  title={ChID: A Large-scale Chinese IDiom Dataset for Cloze Test},
  author={Zheng, Chujie and Huang, Minlie and Sun, Aixin},
  booktitle={ACL 2019},  
  year={2019}
}
```

## Update 190702

The file `wordList.txt` used in baselines (both for paper and for competition) has been uploaded. 

Note that due to the potential differences in equipments and word segmentation tools, your segmentation results may not perfectly match with the vocabulary we provide. For the sake of performance, we suggest you do the segmentation and get the vocabulary list by yourself.

## Update 190629

The data and baseline codes for the competition are uploaded! Please refer to `Competition` for more details!

## Update 190628

The codes for baseline in the paper are uploaded! Please refer to `Codes for baseline` for more details!

### Competition

We are also organizing a competition based on our ChID dataset, and [here](https://biendata.com/competition/idiom/) is the website. The adapted corpus establishes up connections between blanks, and adopts a new type of problem. A list of passages (not an isolated one) is provided and the answers need to be selected from a given set of candidate idioms with fixed length (for more details, please refer to the competition website). 

The public data contains the training data (both the passages with blanks and the golden answers), the development data (only the passages, and the answers will be available later) and the corpus of idiom explanations.

The baselines of the competition are [Attentive Reader](https://arxiv.org/abs/1506.03340) and [BERT](https://arxiv.org/abs/1810.04805).

The data and baseline codes for the competition will be uploaded later.

## Update 190605

The download link of **Train** corpus is available! Please refer to `Data for paper` for more details!
