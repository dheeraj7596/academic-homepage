+++
abstract = "RL-based techniques can be used to search for prompts that when fed into a target language model maximize a set of user-specified reward functions. However, in many target applications, the natural reward functions are in tension with one another -- for example, content preservation vs. style matching in style transfer tasks. Current techniques focus on maximizing the average of reward functions, which does not necessarily lead to prompts that achieve balance across rewards -- an issue that has been well-studied in the multi-objective and robust optimization literature. In this paper, we adapt several techniques for multi-objective optimization to RL-based discrete prompt optimization -- two that consider volume of the Pareto reward surface, and another that chooses an update direction that benefits all rewards simultaneously. We conduct an empirical analysis of these methods on two NLP tasks: style transfer and machine translation, each using three competing reward functions. Our experiments demonstrate that multi-objective methods that directly optimize volume perform better and achieve a better balance of all rewards than those that attempt to find monotonic update directions."
authors = ["Yasaman Jafari", "Dheeraj Mekala", "Rose Yu", "Taylor Berg-Kirkpatrick"]
date = "2024-02-15"
draft = "false"
image_preview = ""
math = true
publication_types = ["3"]
publication = "Preprint"
publication_short = "Arxiv"
featured = false
title = "MORL-Prompt: An Empirical Analysis of Multi-Objective Reinforcement Learning for Discrete Prompt Optimization"
url_pdf = "https://arxiv.org/pdf/2402.11711.pdf"
url_code = ""
+++