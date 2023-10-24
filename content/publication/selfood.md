+++
abstract = "Deep neural classifiers trained with cross-entropy loss (CE loss) often suffer from poor calibration, necessitating the task of out-of-distribution (OOD) detection. Traditional supervised OOD detection methods require expensive manual annotation of in-distribution and OOD samples. To address the annotation bottleneck, we introduce SELFOOD, a self-supervised OOD detection method that requires only in-distribution samples as supervision. We cast OOD detection as an inter-document intra-label (IDIL) ranking problem and train the classifier with our pairwise ranking loss, referred to as IDIL loss. Specifically, given a set of in-distribution documents and their labels, for each label, we train the classifier to rank the softmax scores of documents belonging to that label to be higher than the scores of documents that belong to other labels. Unlike CE loss, our IDIL loss function reaches zero when the desired confidence ranking is achieved and gradients are backpropagated to decrease probabilities associated with incorrect labels rather than continuously increasing the probability of the correct label. Extensive experiments with several classifiers on multiple classification datasets demonstrate the effectiveness of our method in both coarse- and fine-grained settings."
authors = ["Dheeraj Mekala", "Adithya Samavedhi", "Chengyu Dong", "Jingbo Shang"]
date = "2023-10-24"
draft = "false"
image_preview = ""
math = true
publication_types = ["1"]
publication = "The Findings of 2022 Conference on Empirical Methods in Natural Language Processing, Singapore"
publication_short = "EMNLP Findings 2023"
featured = false
title = "SELFOOD: Self-Supervised Out-Of-Distribution Detection via Learning to Rank"
url_pdf = "https://arxiv.org/pdf/2305.14696.pdf"
url_code = "https://github.com/dheeraj7596/SELFOOD"
+++