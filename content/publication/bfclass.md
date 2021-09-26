+++
abstract = "Backdoor attack introduces artificial vulnerabilities into the model by poisoning a subset of the training data via injecting triggers and modifying labels. Various trigger design strategies have been explored to attack text classifiers, however, defending such attacks remains an open problem. In this work, we propose BFClass, a novel efficient backdoor-free training framework for text classification. The backbone of BFClass is a pre-trained discriminator that predicts whether each token in the corrupted input was replaced by a masked language model. To identify triggers, we utilize this discriminator to locate the most suspicious token from each training sample and then distill a concise set by considering their association strengths with particular labels. To recognize the poisoned subset, we examine the training samples with these identified triggers as the most suspicious token, and check if removing the trigger will change the poisoned model’s prediction. Extensive experiments demonstrate that BFClass can identify all the triggers, remove 95% poisoned training samples with very limited false alarms, and achieve almost the same performance as the models trained on the benign training data."
authors = ["Zichao Li", "Dheeraj Mekala", "Chengyu Dong", "Jingbo Shang"]
date = "2021-09-12"
draft = "false"
image_preview = ""
math = true
publication_types = ["1"]
publication = "The Findings of 2020 Conference on Empirical Methods in Natural Language Processing, Punta Cana, Dominican Republic"
publication_short = "EMNLP Findings 2021"
featured = false
title = "BFClass: A Backdoor-free Text Classification Framework"
url_pdf = "https://arxiv.org/pdf/2109.10856.pdf"
url_code = "https://github.com/dheeraj7596/BFClass"
+++