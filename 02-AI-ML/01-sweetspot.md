---
title: Brand Recommendation
authors:
  - name: Myeongseok Gwon
    affiliations: Sweetspot
---

:::{figure} ../images/sweetspot.png
:label: sweetspot
:width: 100%
:align: center
:::

::::{grid} 1 1 2 2

:::{card}
:header: **Problem**
- Lack of a model that recommends suitable brands for vacant units by considering both commercial district and brand characteristics
- Existing approaches only consider simple factors like purchasing power and brand power, ignoring complex interactions between district features (e.g., foot traffic) and brand-specific attributes
:::

:::{card}
:header: **Solution**
- We perform sales prediction modeling on annual sales data from brand franchise stores
- Models based on DNN and GNN that consider non-linearities such as interaction terms between commercial district characteristics and brand characteristics showed better performance as expected
:::

::::

:::{card}
:header: **Contributions**
- Problem definition and preprocessing raw data into a format suitable for modeling
- Implementation of multiple models including HinSage-based GNN model
::: 