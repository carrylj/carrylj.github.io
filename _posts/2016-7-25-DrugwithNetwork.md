---
layout: post
title: Drug target proteins prediction with network properties
description: Yanghe Feng, Tengjiao Wang
category: "paper"
image: assets/images/pic01.jpg
---

Motivation: The identification of drug target proteins can certainly benefit new drug development. With the advances in high throughput sequencing technologies, proteins are studied systematically as a network namely protein-protein interaction (PPI) network. PPI plays a fundamental role in many biological processes. Therefore, it provides us a better way to understand drug and protein interaction. In this paper, we analyzed the drug target protein’s interaction network and extracted the physical and chemical properties from protein sequence information. Based both of the network and individual information, the potential drug target proteins are predicted to help identify new drug targets.<!--excerpt-->
Result: The list of drug target proteins and its corresponding dataset includes 1361 proteins with interaction network structures and chemical properties. They are divided into two parts: drug target dataset and pending test dataset. The former consists of 151 known drug target proteins, and the latter contains 1210 proteins which are unknown whether they are drug target proteins or not. From the above data, we trained the drug target proteins classifier by which this paper predicts 102 proteins from pending test dataset. To guarantee the classifier is not overfitting, we tested it by 10 fold cross validation. The results show that the accuracy of our classifier is 82.01%. Some of our prediction results were found as published new drug targets in previous studies.