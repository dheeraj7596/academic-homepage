+++
abstract = "Multilingual transformer language models have recently attracted much attention from researchers and are used in cross-lingual transfer learning for many NLP tasks such as text classification and named entity recognition. However, similar methods for transfer learning from monolingual text to code-switched text have not been extensively explored mainly due to the following challenges: (1) Codeswitched corpus, unlike monolingual corpus, consists of more than one language and existing methods can’t be applied efficiently, (2) Code-switched corpus is usually made of resource-rich and low-resource languages and upon using multilingual pre-trained language models, the final model might bias towards resource-rich language. In this paper, we focus on code-switched sentiment analysis where we have a labelled resource-rich language dataset and unlabelled code-switched data. We propose a framework that takes the distinction between resource-rich and low-resource language into account. Instead of training on the entire code-switched corpus at once, we create buckets based on the fraction of words in the resource-rich language and progressively train from resource-rich language dominated samples to low-resource language dominated samples. Extensive experiments across multiple language pairs demonstrate that progressive training helps low-resource language dominated samples."
authors = ["Sudhanshu Ranjan", "Dheeraj Mekala", "Jingbo Shang"]
date = "2022-05-24"
draft = "false"
image_preview = ""
math = true
publication_types = ["1"]
publication = "The Findings of 2022 Conference on Empirical Methods in Natural Language Processing, Abu Dhabi, United Arab Emirates"
publication_short = "EMNLP 2022"
featured = false
title = "Progressive Sentiment Analysis for Code-Switched Text Data"
url_pdf = "https://arxiv.org/pdf/2210.14380.pdf"
url_code = "https://github.com/s1998/progressiveTrainCodeSwitch"
+++