---
layout: home
---

ICML 2024: [Oral](https://icml.cc/virtual/2024/oral/35521) ([Keynote](docs/Arrows_of_Time_for_LLMs.ICML2024_oral.key), [pdf](docs/Arrows_of_Time_for_LLMs.ICML2024_oral.pdf)) | [Poster](https://icml.cc/virtual/2024/poster/33931) ([pdf](docs/Arrows_of_Time_for_LLMs.ICML2024_poster.pdf))  
Arxiv paper: [here](https://arxiv.org/abs/2401.17505)  
Code used in our experiments: [here](https://github.com/frotaur/LLM-Arrows-of-Time)

[![Arrows of Time ICML 2024 poster](docs/Arrows_of_Time_for_LLMs.ICML2024_poster.png)](docs/Arrows_of_Time_for_LLMs.ICML2024_poster.pdf)

We study the probabilistic modeling performed by Autoregressive Large Language Models (LLMs) through the angle of time directionality, addressing a question first raised in (Shannon, 1951). For large enough models, we empirically find a time asymmetry in their ability to learn natural language: a difference in the average log-perplexity when trying to predict the next token versus when trying to predict the previous one. This difference is at the same time subtle and very consistent across various modalities (language, model size, training time, ...). Theoretically, this is surprising: from an information-theoretic point of view, there should be no such difference. We provide a theoretical framework to explain how such an asymmetry can appear from sparsity and compu- tational complexity considerations, and outline a number of perspectives opened by our results.


---

![English vs French validation losses ](figures/en-fr.train-valid.combined_with_inset.svg)

{{< legend >}}
English vs French validation losses (French training losses in the zoom-in, early loss values cropped for readability). 
{{< /legend >}}

{{< empty "3em" >}}

![BW/FW losses percentage difference for different context lengths](figures/fr-en.attentions.svg)

{{< legend >}}
BW/FW losses percentage difference for different context lengths.
{{< /legend >}}

{{< empty "3em" >}}

![Validation loss curves for several languages, in FW and BW training.](figures/all-med-lang.png)

{{< legend >}}
Validation loss curves for several languages, in FW and BW training. Consistently, during training, the BW loss is higher than its FW counterpart. This persists through the warm restart of the learning rate, which causes a bump in the loss.
{{< /legend >}}

{{< empty "3em" >}}

![Models loss at the end of training vs → sparsity.](figures/sparsities.svg)

{{< legend >}}
Models loss at the end of training vs → sparsity.
{{< /legend >}}

{{< empty "3em" >}}

---

{{< youtube 1recdRrkg_Y >}}

---
