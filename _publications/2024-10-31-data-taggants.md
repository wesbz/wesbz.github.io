---
title: "Data Taggants: Dataset Ownership Verification via Harmless Targeted Data Poisoning"
header:
    teaser: "/assets/images/pubs/data-taggants/teaser.png"
authors:
    - name: Wassim (Wes) Bouaziz
      url: https://wesbz.github.io
    - name: Nicolas Usunier
    - name: El Mahdi El Mhamdi
      url: https://elmahdielmhamdi.com/
venue: "International Conference on Learning Representations (ICLR) 2025"
arxiv: "https://arxiv.org/abs/2410.09101"
# code: "https://github.com/wesbz/okok"
pdf: "https://arxiv.org/pdf/2410.09101"
bib: "/assets/pubs/data-taggants.txt"
excerpt: ""
---

{% for author in page.authors %} [{{ author.name }}]({{ author.url }}){% if forloop.last == false %}, {% endif %} {% endfor %}

In this work, we introduce **Data Taggants**, a novel approach for dataset ownership verification that leverages targeted data poisoning. Our method allows dataset owners to embed unique identifiers into their datasets, enabling them to prove ownership without compromising the integrity of the data. This is achieved by injecting harmless perturbations that do not affect the performance of models trained on the dataset.
This approach not only proves to be more effective than existing methods but also offers theoretical guarantees on the false detection rate.