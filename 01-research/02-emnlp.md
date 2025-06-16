---
title: Mnemonic Generation
authors:
  - name: Myeongseok Gwon
    affiliations: CMU (Carnegie Mellon University)
venue:
  title: EMNLP 2025 (UNDER REVIEW)
  url: https://2025.emnlp.org/
---

:::{figure} ../images/emnlp.png
:label: emnlp
:width: 100%
:align: center
:::

::::{grid} 1 1 2 2

:::{card}
:header: **Problem**
- Lack of mnemonic generation models for typologically distinct language pairs. (e.g. Korean and English)
- Previous work only supports English-only. It does not address the cross-lingual IPA variation.
:::

:::{card}
:header: **Solution**
1. **Design and Implementation**
    - Leveraging previous work with English-only support
    - Applying our own transliteration methodology to retrieve keywords.
2. **Validation**: Automated evaluation and human experiments.
:::

::::

:::{card}
:header: **Contributions** (Co-first author)
- Designed and implemented the complete pipeline from English words to verbal cue.
- Developed automated evaluation methods and designed/implemented ablation studies.
- Participated in human experiment design.
::: 