---
title: "The Impact of Differential Privacy on Recommendation Accuracy amd Popularity Bias"
authors: "Peter Müllner, Elisabeth Lex, Markus Schedl, Dominik Kowald"
collection: publications
permalink: /publication/impactofdp
excerpt: "We study the impact of Differential Privacy (DP) on recommendation accuracy and popularity bias by comparing recommendation lists generated with and without DP. We find that nearly all users receive different recommendations than without DP and that large parts of the recommendation lists are different. Plus, we observe a substantial drop in recommendation accuracy and a sharp increase in popularity bias. Furthermore, especially user groups that prefer unpopular items experience a substantial increase in popularity bias when DP is applied.
date: 2024-03-15
venue: '46th European Conference on Information Retrieval (ECIR)'
paperurl: 'http://pmuellner.github.io/files/impactofdp.pdf'
citation: 'Müllner, P., Lex, E. Schedl, M., Kowald D. (2024). The Impact of Differential Privacy on Recommendation Accuracy amd Popularity Bias. In Advances in Information Retrieval: 46th European Conference on Information Retrieval, ECIR 2024, Glasgow, UK, Proceedings, Part IV (pp. 483-484). Cham: Springer Nature Switzerland.'
slides: /files/userprivacyinrecsys_slides.pdf
---

Collaborative filtering-based recommender systems leverage vast amounts of behavioral user data, which poses severe privacy risks. Thus, often random noise is added to the data to ensure Differential Privacy (DP). However, to date, it is not well understood in which ways this impacts personalized recommendations. In this work, we study how DP affects recommendation accuracy and popularity bias when applied to the training data of state-of-the-art recommendation models. Our findings are three-fold: First, we observe that nearly all users' recommendations change when DP is applied. Second, recommendation accuracy drops substantially while recommended item popularity experiences a sharp increase, suggesting that popularity bias worsens. Finally, we find that DP exacerbates popularity bias more severely for users who prefer unpopular items than for users who prefer popular items.