# BiGCN

Convolution over Hierarchical Syntactic and Lexical Graphs for Aspect Level Sentiment Analysis
* Code and preprocessed dataset for [EMNLP 2020](https://2020.emnlp.org/papers/main) paper titled "[Convolution over Hierarchical Syntactic and Lexical Graphs for Aspect Level Sentiment Analysis](https://www.aclweb.org/anthology/2020.emnlp-main.286/)" 

We will release the code and data soon.
Datasets:Twitter,Lap14,Rest14,Rest15,Rest16
## Requirements
@@ -19,3 +23,28 @@ and
python -m spacy download en
```
* Download pretrained GloVe embeddings with this [link](http://nlp.stanford.edu/data/wordvecs/glove.840B.300d.zip) and extract `glove.840B.300d.txt` into `glove/`.



## Citation

If you use the code in your paper, please kindly star this repo and cite our paper
'''
@inproceedings{DBLP:conf/emnlp/ZhangQ20,
  author    = {Mi Zhang and
               Tieyun Qian},
  title     = {Convolution over Hierarchical Syntactic and Lexical Graphs for Aspect
               Level Sentiment Analysis},
  booktitle = {Proceedings of the 2020 Conference on Empirical Methods in Natural
               Language Processing, {EMNLP} 2020, Online, November 16-20, 2020},
  pages     = {3540--3549},
  year      = {2020},
  crossref  = {DBLP:conf/emnlp/2020-1},
  url       = {https://www.aclweb.org/anthology/2020.emnlp-main.286/},
  timestamp = {Thu, 19 Nov 2020 16:13:16 +0100},
  biburl    = {https://dblp.org/rec/conf/emnlp/ZhangQ20.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}

'''
* Code of this repo heavily relies on [ABSA-PyTorch](https://github.com/songyouwei/ABSA-PyTorch)
