---
title: "Multi-label Active Learning"
layout: single-portfolio
excerpt: "<img src='/images/research/GPB2M.PNG' alt=''>"
collection: research
order_number: 10
header: 
  og_image: "research/GPB2M.PNG"
---

In this research we propose to conduct multi-label active learning (ML-AL) through a novel integrated Gaussian Process-Bayesian Bernoulli Mixture model (GP-B2M) to accurately quantify a data sample’s overall contribution to a correlated label space and choose the most informative samples for cost-effective annotation. In particular, the B2M encodes label correlations using a Bayesian Bernoulli mixture of label clusters, where each mixture component corresponds to a global pattern of label correlations. To tackle highly sparse labels under AL, the B2M is further integrated with a predictive GP to connect data features as an effective inductive bias and achieve a feature-component-label mapping. The GP predicts coefficients of mixture components that help to recover the final set of labels of a data sample. A novel auxiliary variable based variational inference algorithm is developed to tackle the non-conjugacy introduced along with the mapping process for efficient end-to-end posterior inference. The model also outputs a predictive distribution that provides both the label prediction and their correlations in the form of a label covariance matrix. A principled sampling function is designed accordingly to naturally capture both the feature uncertainty (through GP) and label covariance (through B2M) for effective data sampling. Experiments on real-world multi-label datasets demonstrate the state-of-the-art AL performance of the proposed model.
## Article

Weishi Shi, Dayou Yu, Qi Yu. "A gaussian process-bayesian bernoulli mixture model for multi-label active learning" *NeurIPS 2021*.


