---
title: Drug Labeling Document Summarization
authors:
  - name: Myeongseok Gwon
    affiliations: HDMedi
---

:::{figure} ../images/hdmedi.png
:label: hdmedi
:width: 100%
:align: center
:::

::::{grid} 1 1 2 2

:::{card}
:header: **Problem**
- Drug Labeling Documents are lengthy, making it difficult to understand important information, which is why experts manually create summaries. Due to the high labor requirements, approximately 80% of medications still lack summary documents.
- Lack of a model that summarizes drug labeling documents in a way that is easy to understand for patients.
:::

:::{card}
:header: **Solution**
1. **Implementation**: We used a pre-trained LLM and improved the quality of the summary by prompt engineering. Especially, we found that preprocessing the input in XML format rather than plain text can improve accuracy.
2. **Validation**: We used metrics such as BERT, BLEU, METEOR, and ROGUE-L to evaluate the performance.
:::

::::

:::{card}
:header: **Contributions**
- Leading a team of 2 undergraduate interns
- Literature research, prompt engineering, and design of summary evaluation methods
::: 