+++
abstract = "Manually annotating datasets requires domain experts to read through many documents and carefully label them, which is often expensive. Recently, pre-trained generative language models (GLMs) have demonstrated exceptional abilities in generating text which motivates to leverage them for generative data augmentation. We improve generative data augmentation by formulating the data generation as context generation task and use question answering (QA) datasets for intermediate training. Specifically, we view QA to be more as a format than of a task and train GLMs as context generators for a given question and its respective answer. Then, we cast downstream tasks into question answering format and adapt the fine-tuned context generators to the target task domain. Finally, we use the fine-tuned GLM to generate relevant contexts, which is further used as synthetic training data for their corresponding tasks. We perform extensive experiments, case studies, and ablation studies on multiple sentiment and topic classification datasets and demonstrate substantial improvements in performance in few-shot, zero-shot settings. Remarkably, on the SST2 dataset, intermediate training on SocialIQA dataset achieves an improvement of 40% on Macro-F1 score. Through thorough analyses, we observe that QA datasets that requires highlevel reasoning abilities (e.g., abstractive and common-sense QA datasets) tend to give the best boost in performance in both few-shot and zero-shot settings."
authors = ["Dheeraj Mekala", "Tu Vu", "Timo Schick", "Jingbo Shang"]
date = "2022-05-25"
draft = "false"
image_preview = ""
math = true
publication_types = ["1"]
publication = "The 2022 Conference on Empirical Methods in Natural Language Processing, Abu Dhabi, United Arab Emirates"
publication_short = "EMNLP 2022"
featured = false
title = "Leveraging QA Datasets to Improve Generative Data Augmentation"
url_pdf = "https://arxiv.org/pdf/2205.12604.pdf"
url_code = "https://github.com/dheeraj7596/CONDA"
+++