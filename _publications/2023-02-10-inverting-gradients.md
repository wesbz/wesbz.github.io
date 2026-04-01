---
title: "Inverting Gradient Attacks Makes Powerful Data Poisoning"
header:
    teaser: "/assets/images/pubs/inverting-gradients/teaser.png"
authors:
    - name: Wassim (Wes) Bouaziz
      url: https://wesbz.github.io
    - name: El Mahdi El Mhamdi
      url: https://elmahdielmhamdi.com/
    - name: Nicolas Usunier
venue: "Transactions on Machine Learning Research (TMLR) 2025"
arxiv: "https://arxiv.org/abs/2410.21453"
# code: "https://github.com/wesbz/okok"
pdf: "https://arxiv.org/pdf/2410.21453"
bib: "/assets/pubs/inverting-gradients.txt"
excerpt: ""
---

{% for author in page.authors %} [{{ author.name }}]({{ author.url }}){% if forloop.last == false %}, {% endif %} {% endfor %}

This work demonstrates, in a theoretical worst-case scenario, that data poisoning attacks can mimick gradient attacks by inverting gradients. This work demonstrates an empirical upper-bound on the damage that can be achieved by data poisoning attacks. While more constrained than gradient attacks, we demonstrate that data poisoning attacks still have room for effective attacks.