---
title: "Iteration Head: A Mechanistic Study of Chain-of-Thought"
header:
    teaser: "/assets/images/pubs/iteration-head/teaser.png"
authors:
    - name: Vivien Cabannes
      url: https://viviencabannes.github.io/
    - name: Charles Arnal
      url: https://charlesarnal.github.io/
    - name: Wassim (Wes) Bouaziz
      url: https://wesbz.github.io
    - name: Alice Yang
    - name: Francois Charton
      url: https://f-charton.github.io/about/
    - name: Julia Kempe
      url: https://cims.nyu.edu/~kempe/
venue: "Advances in Neural Information Processing Systems (NeurIPS) 2024"
arxiv: "https://arxiv.org/abs/2406.02128"
code: "https://github.com/facebookresearch/pal/tree/main/projects/cot"
pdf: "https://arxiv.org/pdf/2406.02128"
bib: "/assets/pubs/iteration-head.txt"
excerpt: ""
---

{% for author in page.authors %} [{{ author.name }}]({{ author.url }}){% if forloop.last == false %}, {% endif %} {% endfor %}
