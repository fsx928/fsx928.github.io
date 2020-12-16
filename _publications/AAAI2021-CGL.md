---
title: "Collaborative Group Learning"
collection: publications
permalink: /publications/AAAI2021-CGL
venue: "The Thirty-Fifth AAAI conference on Artificial Intelligence (AAAI-21)"
date: 2021-2-2
citation: '<b>Shaoxiong Feng</b>, Hongshen Chen, Xuancheng Ren, Zhuoye Ding, Kan Li, and Xu Sun. <i>The 35th AAAI conference on Artificial Intelligence</i>. <b>AAAI 2021</b>.'
---
Link: [[arxiv](https://arxiv.org/abs/2009.07712)]


## Abstract
Collaborative learning has successfully applied knowledge transfer to guide a pool of small student networks towards robust local minima. However, previous approaches typically struggle with drastically aggravated student homogenization when the number of students rises. In this paper, we propose Collaborative Group Learning, an efficient framework that aims to diversify the feature representation and conduct an effective regularization. Intuitively, similar to the human group study mechanism, we induce students to learn and exchange different parts of course knowledge as collaborative groups. First, each student is established by randomly routing on a modular neural network, which facilitates flexible knowledge communication between students due to random levels of representation sharing and branching. Second, to resist the student homogenization, students first compose diverse feature sets by exploiting the inductive bias from sub-sets of training data, and then aggregate and distill different complementary knowledge by imitating a random sub-group of students at each time step. Overall, the above mechanisms are beneficial for maximizing the student population to further improve the model generalization without sacrificing computational efficiency. Empirical evaluations on both image and text tasks indicate that our method significantly outperforms various state-of-the-art collaborative approaches whilst enhancing computational efficiency.
