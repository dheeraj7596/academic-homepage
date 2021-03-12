+++
abstract = "In this paper, we explore to conduct text classification with extremely weak supervision, i.e., only relying on the surface text of class names. This is a more challenging setting than the seed-driven weak supervision, which allows a few seed words per class. We opt to attack this problem from a representation learning perspective -- ideal document representations should lead to very close results between clustering and the desired classification. In particular, one can classify the same corpus differently (e.g., based on topics and locations), so document representations must be adaptive to the given class names. We propose a novel framework X-Class to realize it. Specifically, we first estimate comprehensive class representations by incrementally adding the most similar word to each class until inconsistency appears. Following a tailored mixture of class attention mechanisms, we obtain the document representation via a weighted average of contextualized token representations. We then cluster and align the documents to classes with the prior of each document assigned to its nearest class. Finally, we pick the most confident documents from each cluster to train a text classifier. Extensive experiments demonstrate that X-Class can rival and even outperform seed-driven weakly supervised methods on 7 benchmark datasets."
authors = ["Zihan Wang", "Dheeraj Mekala", "Jingbo Shang"]
date = "2021-03-11"
draft = "false"
image_preview = ""
math = true
publication_types = ["1"]
publication = "North American Chapter of the Association for Computational Linguistics, 2021, Mexico"
publication_short = "NAACL 2021"
featured = false
title = "X-Class: Text Classification with Extremely Weak Supervision"
url_pdf = "https://arxiv.org/pdf/2010.12794.pdf"
url_code = "https://github.com/ZihanWangKi/XClass"
+++
