---
title: "Robustness of Meta Matrix Factorization Against Strict Privacy Constraints"
authors: "Peter Müllner, Dominik Kowald, and Elisabeth Lex"
collection: publications
permalink: /publication/robustnessofmetamf
excerpt: "we explore the reproducibility of MetaMF, a meta matrix factorization framework introduced by Lin et al and study the impact of meta learning on the accuracy of MetaMF’s recommendations. Also, we investigate the robustness of MetaMF against strict privacy constraints, i.e., how much data a user is willing to share with the recommender system. Our study illustrates that we can reproduce most of Lin et al.’s results. Plus, meta learning is essential for MetaMF’s robustness against strict privacy constraints."
date: 2021-03-30
venue: '43rd European Conference on IR Research, ECIR 2021'
paperurl: 'http://pmuellner.github.io/files/robustnessofmetamf.pdf'
citation: 'Muellner, P., Kowald, D., & Lex, E. (2021). Robustness of meta matrix factorization against strict privacy constraints. In Advances in Information Retrieval: 43rd European Conference on IR Research, ECIR 2021, Virtual Event, March 28–April 1, 2021, Proceedings, Part II 43 (pp. 107-119). Springer International Publishing.'
codeurl: https://github.com/pmuellner/robustnessofmetamf
slides: https://github.com/pmuellner/robustnessofmetamf_slides.pdf
---

In this paper, we explore the reproducibility of MetaMF, a meta matrix factorization framework introduced by Lin et al. MetaMF employs meta learning for federated rating prediction to preserve users’ privacy. We reproduce the experiments of Lin et al. on five datasets, i.e., Douban, Hetrec-MovieLens, MovieLens 1M, Ciao, and Jester. Also, we study the impact of meta learning on the accuracy of MetaMF’s recommendations. Furthermore, in our work, we acknowledge that users may have different tolerances for revealing information about themselves. Hence, in a second strand of experiments, we investigate the robustness of MetaMF against strict privacy constraints. Our study illustrates that we can reproduce most of Lin et al.’s results. Plus, we provide strong evidence that meta learning is essential for MetaMF’s robustness against strict privacy constraints.
