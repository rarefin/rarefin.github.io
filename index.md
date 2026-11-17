---
layout: homepage
---

## About

I'm a final-year Ph.D. candidate at [Mila](https://mila.quebec/en) and Université de Montréal, advised by Irina Rish. I study how large language models learn: how the optimizer, the architecture and the training data shape what a model ends up representing, and how to use that understanding to train better models. I usually start from a precise question, answer it with theory where I can, and then test the answer on real language models.

I've done research internships at Meta (twice), Amazon, Samsung and ServiceNow, and have worked with Yoshua Bengio and Yann LeCun.

What I'm working on:

- **Optimization and training dynamics:** how training choices like weight decay keep affecting a run long after they end, and how to tune them on small models and carry them over to large ones ([preprint, 2026](https://arxiv.org/abs/2611.17876)).
- **Architecture:** which blocks are worth their parameters, such as when SwiGLU-style gating beats simpler MLPs ([CP-MLPs, NeurIPS 2026](https://arxiv.org/abs/2611.13647)), and memory-efficient alternatives to attention ([TT-Delta, COLM 2026 workshop](https://openreview.net/forum?id=bnreIEZxps)).
- **Data attribution:** estimating how groups of training examples interact, where they reinforce or duplicate each other, instead of scoring each example on its own ([preprint, 2026](https://arxiv.org/abs/2610.24721)).
- **Representations and reasoning:** how internal representations collapse during training and why that hurts multi-step reasoning ([Seq-VCR, ICLR 2025](https://arxiv.org/abs/2411.02344); [Layer by Layer, ICML 2025](https://arxiv.org/abs/2502.02013)).
- **Safety evaluation:** how to choose audit probes when the model being audited can adapt to them ([NeurIPS 2026 workshop](assets/files/papers/redundant-probes-auditing.pdf)).

{% include news.html %}

{% include publications.html %}

{% include experience.html %}

{% include service.html %}
