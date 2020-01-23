---
title: "Structured Recommendation"
date: 2017-01-01
publishDate: 2019-12-29T23:55:04.489505Z
authors: ["Dawei Chen", "Lexing Xie", "Aditya Krishna Menon", "Cheng Soon Ong"]
publication_types: ["1"]
abstract: "Current recommender systems largely focus on static, unstructured content. In many scenarios, we would like to recommend content that has structure, such as a trajectory of points-of-interests in a city, or a playlist of songs. Dubbed Structured Recommendation, this problem differs from the typical structured prediction problem in that there are multiple correct answers for a given input. Motivated by trajectory recommendation, we focus on sequential structures but in contrast to classical Viterbi decoding we require that valid predictions are sequences with no repeated elements. We propose an approach to sequence recommendation based on the structured support vector machine. For prediction, we modify the inference procedure to avoid predicting loops in the sequence. For training, we modify the objective function to account for the existence of multiple ground truths for a given input. We also modify the loss-augmented inference procedure to exclude the known ground truths. Experiments on real-world trajectory recommendation datasets show the benefits of our approach over existing, non-structured recommendation approaches."
featured: false
publication: "*Arxiv preprint*"
---
