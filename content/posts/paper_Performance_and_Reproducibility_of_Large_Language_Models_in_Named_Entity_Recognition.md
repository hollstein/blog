---
date: '2024-12-12T17:46:46+01:00'
draft: false
title: 'Paper published in Drug Safety: Performance and Reproducibility of Large Language Models in Named Entity Recognition: Considerations for the Use in Controlled Environments'
---

Please find the papper here:  https://link.springer.com/article/10.1007/s40264-024-01499-1

Jürgen and I explored extensively how we can apply generative AI in the form of large language models in controlled environments like pharmacovigilance.
One prerequisite for these use cases is the reproducibility of generated text. We show that open-source LLMs ensure reproducibility and provide good results by fine-tuning, few-shot learning, and guided generation. At the time of doing the research for the paper, we found that reproducibility was not achievable out of the box with models from OpenAI even when we followed all means to achieve it, like setting generation temperature to zero. This issue needs to be addressed for the complete lifetime of the downstream application, which might be a more contractual and legal than technical challenge. However, their zero-shot performance is a good starting point to support generating training-data generation to train smaller, locally run models for which reproducibility can be easily guaranteed for the complete lifetime of the use case. All the details in the paper!
