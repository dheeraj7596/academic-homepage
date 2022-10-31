+++
abstract = "Existing text classification methods mainly focus on a fixed label set, whereas many real-world applications require extending to new fine-grained classes as the number of samples per label increases. To accommodate such requirements, we introduce a new problem called coarse-to-fine grained classification, which aims to perform fine-grained classification on coarsely annotated data. Instead of asking for new fine-grained human annotations, we opt to leverage label surface names as the only human guidance and weave in rich pre-trained generative language models into the iterative weak supervision strategy. Specifically, we first propose a label-conditioned fine-gtuning formulation to attune these generators for our task. Furthermore, we devise a regularization objective based on the coarse-fine label constraints derived from our problem setting, giving us even further improvements over the prior formulation. Our framework uses the fine-tuned generative models to sample pseudo-training data for training the classifier, and bootstraps on real unlabeled data for model refinement. Extensive experiments and case studies on two real-world datasets demonstrate superior performance over SOTA zero-shot classification baselines."
authors = ["Dheeraj Mekala", "Varun Gangal", "Jingbo Shang"]
date = "2021-09-12"
draft = "false"
image_preview = ""
math = true
publication_types = ["1"]
publication = "The 2021 Conference on Empirical Methods in Natural Language Processing, Punta Cana, Dominican Republic"
publication_short = "EMNLP 2021"
featured = false
title = "Coarse2Fine: Fine-grained Text Classification on Coarsely-grained Annotated Data"
url_pdf = "https://arxiv.org/pdf/2109.10856.pdf"
url_code = "https://github.com/dheeraj7596/C2F"
+++