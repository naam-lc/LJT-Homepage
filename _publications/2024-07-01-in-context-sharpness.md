---
title: "In-Context Sharpness as Alerts: An Inner Representation Perspective for Hallucination Mitigation"
collection: publications
category: conferences
permalink: /publication/2024-07-01-in-context-sharpness
excerpt: 'We discover a pattern associated with hallucinations: correct generations tend to have sharper context activations in the hidden states of in-context tokens; we propose an entropy-based metric and incorporate it into decoding to improve factuality.'
date: 2024-07-01
venue: 'ICML 2024'
paperurl: 'https://arxiv.org/abs/2403.01548'
citation: 'Shiqi Chen, Miao Xiong, Junteng Liu, Zhengxuan Wu, Teng Xiao, Siyang Gao, Junxian He. (2024). &quot;In-Context Sharpness as Alerts: An Inner Representation Perspective for Hallucination Mitigation.&quot; <i>Proceedings of the 41st International Conference on Machine Learning (ICML)</i>.'
---

We discover a pattern associated with hallucinations: correct generations tend to have *sharper* context activations in the hidden states of the in-context tokens, compared to that of the incorrect generations. Leveraging this signal, we propose an entropy-based metric to quantify the "sharpness" among the in-context hidden states and incorporate it into the decoding process, i.e, use the entropy value to adjust the next token prediction distribution to improve the factuality and overall quality of the generated text.

**Paper:** [https://arxiv.org/abs/2403.01548](https://arxiv.org/abs/2403.01548)
