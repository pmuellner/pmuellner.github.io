---
title: "ReuseKNN: Neighborhood Reuse for Differentially Private KNN-Based Recommendations"
authors: "Peter Müllner, Elisabeth Lex, Markus Schedl, Dominik Kowald"
collection: publications
permalink: /publication/reuseknn
excerpt: "To reduce the privacy risk of users in k nearest neighbor recommender systems, existing work applies differential privacy by adding randomness to the neighbors’ ratings, which unfortunately reduces the accuracy of UserKNN. In this work, we introduce ReuseKNN, a novel differentially private KNN-based recommender system. The main idea is to identify small but highly reusable neighborhoods so that (i) only a minimal set of users requires protection with differential privacy and (ii) most users do not need to be protected with differential privacy since they are only rarely exploited as neighbors"
date: 2023-08-11
venue: 'ACM Transactions on Intelligent Systems and Technology (TIST)'
paperurl: http://pmuellner.github.io/files/reuseknn.pdf
citation: 'Muellner, P., Lex, E., Schedl, M., Kowald D. ReuseKNN: Neighborhood Reuse for Differentially Private KNN-Based Recommendations. <i>ACM Trans. Intell. Syst. Technol. 14, 5, Article 80, 29 Pages.</i> (2023). https://doi.org/10.1145/3608481'
codeurl: https://github.com/pmuellner/reuseknn
slides:
---

User-based KNN recommender systems (UserKNN) utilize the rating data of a target user's k nearest neighbors in the recommendation process. This, however, increases the privacy risk of the neighbors, since the recommendations could expose the neighbors' rating data to other users or malicious parties. To reduce this risk, existing work applies differential privacy by adding randomness to the neighbors' ratings, which unfortunately reduces the accuracy of UserKNN. In this work, we introduce ReuseKNN, a novel differentially private KNN-based recommender system. The main idea is to identify small but highly reusable neighborhoods so that (i) only a minimal set of users requires protection with differential privacy and (ii) most users do not need to be protected with differential privacy since they are only rarely exploited as neighbors. In our experiments on five diverse datasets, we make two key observations. Firstly, ReuseKNN requires significantly smaller neighborhoods and, thus, fewer neighbors need to be protected with differential privacy compared with traditional UserKNN. Secondly, despite the small neighborhoods, ReuseKNN outperforms UserKNN and a fully differentially private approach in terms of accuracy. Overall, ReuseKNN leads to significantly less privacy risk for users than in the case of UserKNN.
