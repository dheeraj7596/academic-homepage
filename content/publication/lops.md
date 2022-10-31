+++
abstract = "Weakly supervised text classification methods typically train a deep neural classifier based on pseudo-labels. The quality of pseudo-labels is crucial to final performance but they are inevitably noisy due to their heuristic nature, so selecting the correct ones has a huge potential for performance boost. One straightforward solution is to select samples based on the softmax probability scores in the neural classifier corresponding to their pseudo-labels. However, we show through our experiments that such solutions are ineffective and unstable due to the erroneously high-confidence predictions from poorly calibrated models. Recent studies on the memorization effects of deep neural models suggest that these models first memorize training samples with clean labels and then those with noisy labels. Inspired by this observation, we propose a novel pseudo-label selection method LOPS that takes learning order of samples into consideration. We hypothesize that the learning order reflects the probability of wrong annotation in terms of ranking, and therefore, propose to select the samples that are learnt earlier. LOPS can be viewed as a strong performance-boost plug-in to most of existing weakly-supervised text classification methods, as confirmed in extensive experiments on four real-world datasets."
authors = ["Dheeraj Mekala", "Chengyu Dong", "Jingbo Shang"]
date = "2022-05-25"
draft = "false"
image_preview = ""
math = true
publication_types = ["1"]
publication = "The Findings of 2022 Conference on Empirical Methods in Natural Language Processing, Abu Dhabi, United Arab Emirates"
publication_short = "EMNLP Findings 2022"
featured = false
title = "LOPS: Learning Order Inspired Pseudo-Label Selection for Weakly Supervised Text Classification"
url_pdf = "https://arxiv.org/pdf/2205.12528.pdf"
url_code = "https://github.com/dheeraj7596/LOPS"
+++