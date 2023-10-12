---
title: "Differential privacy in collaborative filtering recommender systems: a review" 
authors: "Peter Müllner, Elisabeth Lex, Markus Schedl, and Dominik Kowald"
collection: publications
permalink: /publication/dpinrecommendersystems
excerpt: "We review 26 recommendation approaches that apply differential privacy, and we highlight research that improves the trade-off between recommendation quality and user privacy. Also, we classify these approaches based on how they apply DP, i.e., to the user representation, the model updates, or after model training. Finally, we discuss open issues of research on differentially private recommender systems, e.g., considering the relation between privacy and fairness, and the users' different needs for privacy".
date: 2023-10-12
venue: 'Frontiers in Big Data - Recommender Systems'
paperurl: 'http://pmuellner.github.io/files/dpinrecommendersystems.pdf'
citation: 'Müllner, P., Lex, E., Schedl, M., Kowald, D. (2023). Differential privacy in collaborative filtering recommender systems: a review. In <i>Frontiers in Big Data</i> 6 (2023).'
codeurl: 
slides:
---

State-of-the-art recommender systems produce high-quality recommendations to support users in finding relevant content. However, through the utilization of users' data for generating recommendations, recommender systems threaten users' privacy. To alleviate this threat, often, differential privacy is used to protect users' data via adding random noise. This, however, leads to a substantial drop in recommendation quality. Therefore, several approaches aim to improve this trade-off between accuracy and user privacy. In this work, we first overview threats to user privacy in recommender systems, followed by a brief introduction to the differential privacy framework that can protect users' privacy. Subsequently, we review recommendation approaches that apply differential privacy, and we highlight research that improves the trade-off between recommendation quality and user privacy. Finally, we discuss open issues, e.g., considering the relation between privacy and fairness, and the users' different needs for privacy. With this review, we hope to provide other researchers an overview of the ways in which differential privacy has been applied to state-of-the-art collaborative filtering recommender systems.