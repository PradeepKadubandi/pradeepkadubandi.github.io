---
title: "Motion Planner Guided Visuomotor Policy Learning"
collection: publications
permalink: /publication/2021-05-31-paper-demoplanner-number-1
excerpt: 'My research work in RESL Lab @ USC.'
date: 2021-05-31
venue: 'MLMP at ICRA 2021'
paperurl: 'http://pradeepkadubandi.github.io/files/demoplanner.pdf'
citation: 'Will be updated mid 2021'
---
We learn a visuomotor policy from a motion planner where the input of the policy and planner are from different domains. The domain of the planner is a low-dimensional representation of the environment that consists of object poses and shapes whereas the policy observes a high-dimensional visual representation of the environment as input. The goal is to learn a visuomotor policy that imitates the behavior generated by a motion planner. In the training phase, the robot has access to the low-dimensional environment representation, while at inference time only the visual representation is observed. We first train a behavioral cloning policy in the low-dimensional environment representation and an autoencoder in the visual domain. Then, we combine both models into a single policy and fine-tune it on a low amount of demonstration data. In simulated experiments, we demonstrate the effectiveness of our approach and compare it to prior work.

[Download paper here](http://pradeepkadubandi.github.io/files/demoplanner.pdf)

Recommended citation: TBD (Will be modified after uploading the final draft to arxiv)