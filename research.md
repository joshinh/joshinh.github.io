---
layout: post
title: Research
permalink: /research/
---

My research interests broadly lie in the fields of Natural Language Processing and Machine Learning.
Recently, I have also been interested in the theoretical aspects of Machine Learning.

### Publications

* Explore, Propose and Assemble: An Interpretable Model for Multi-Hop Reading Comprehension<br/>
Yichen Jiang <sup>&dagger;</sup>, **Nitish Joshi** <sup>&dagger;</sup>, Yen-chun Chen and Mohit Bansal<br/>
*Proceedings of [ACL 2019](http://www.acl2019.org/EN/index.xhtml), Florence, Italy*<br/>
\[[pdf](https://arxiv.org/pdf/1906.05210.pdf)\] \[[code](https://github.com/jiangycTarheel/EPAr)\]

* Cross-Lingual Training for Automatic Question Generation<br/>
Vishwajeet Kumar, **Nitish Joshi**, Arijit Mukherjee, Ganesh Ramakrishnan and Preethi Jyothi<br/>
*Proceedings of [ACL 2019](http://www.acl2019.org/EN/index.xhtml), Florence, Italy*<br/> 
\[[pdf](https://arxiv.org/pdf/1906.02525.pdf)\] \[[data](https://www.cse.iitb.ac.in/~ganesh/HiQuAD/clqg/)\]

* Coupled Training of Sequence-to-Sequence Models for Accented Speech Recognition<br/>
Vinit Unni <sup>&dagger;</sup>, **Nitish Joshi** <sup>&dagger;</sup> and Preethi Jyothi<br/>
*Submitted to [ICASSP 2020](https://2020.ieeeicassp.org)*

<sup>&dagger;</sup>*Equal Contribution*

### Research Projects

2019

**Learning with Noisy Sequence Labels**<br/>
*Bachelor's Thesis guided by [Prof. Preethi Jyothi](https://www.cse.iitb.ac.in/~pjyothi/)*

Majority of the datasets collected by crowdsourcing tend to have noisy labels. Although there is a lot of theoretical and empirical work for learning with noisy labels for multiclass classification, there is very sparse work for structured outputs such as sequences. We are currently working on the problem of probablistic label aggregation for tasking involving sequences such as Part of Speech tagging and Named Entity Recognition.

**Policy Iteration Lower Bounds for Multi-Action MDPs** [[report]](https://joshinh.github.io/files/CS747_report.pdf)<br/>
*Guide: [Prof. Shivaram K](https://www.cse.iitb.ac.in/~shivaram/) (Course Project)*

Simple Policy Iteration is a type of policy iteration algorithm where the policy of only one improvable state is changed at every step. [Melekopoglou and Condon](https://pdfs.semanticscholar.org/b321/9edc2ce55b2d7f5d45cc014a0d2733ed3051.pdf) showed an exponential lower bound for 2-action MDPs. We generalized the MDPs to k-actions and demonstrate a lower bound of O(k.2<sup>n</sup>).

**Explainable Natural Language Inference**<br/>
*Guide: [Dr. Christopher Malon](http://www.nec-labs.com/christopher-malon) (Internship at NEC Labs, Princeton)*

Simple entailment models try to judge the hypotheses as true, false, or unsupported based on information in a single sentence or group of concatenated sentences, but this information is sometimes insufficient. We constructed datasets for multi-hop NLI by transforming existing multi-hop QA datasets and proposed models which could perform multi-hop reasoning. Our model could also generate explanations for the inferential relationship without any direct supervision.

2018

**Interpretable Multi-hop Reading Comprehension** [[paper]](https://www.aclweb.org/anthology/P19-1261/) <br/>
*Guide: [Prof. Mohit Bansal]() (Internship at UNC Chapel Hill)*

Built interpretable models for multi-hop reading comprehension which searched and assembled important contextual information, by constructing a tree of reasoning chains to answer a given question. By constructing explicit reasoning chains, it was possible to understand the exact evidence used by the model. Achieved strong results on two challenging datasets and also demonstrated the interpretability through various analysis and ablations.

**Cross-lingual Question Generation** [[paper]](https://www.aclweb.org/anthology/P19-1481/)<br/>
*Guide: [Prof. Ganesh Ramakrishnan](https://www.cse.iitb.ac.in/~ganesh/) and [Prof. Preethi Jyothi](https://www.cse.iitb.ac.in/~pjyothi/)*

Many Natural Language Generation tasks assume access to large supervised datasets which may not be available for all languages. We proposed cross-lingual pre-training methods which could leverage information from data rich languages (such as English) to improve performance on the downstream task for low resource languages (such as Hindi). We also released a small Hindi QA dataset along with the work.

**Accent Adaptation for Speech Recognition** <br/> [[report]](https://joshinh.github.io/files/RnD_Report.pdf) <br/>
*Guide: [Prof. Preethi Jyothi](https://www.cse.iitb.ac.in/~pjyothi/)*

Majority of the state-of-the-art automatic speech recognition (ASR) systems for English are trained on the readily available US-accented data and perform poorly on other accents. We introduced domain adversarial training techniques to adapt ASR systems to low resource accents. Extended this work (later in 2019) by proposing a novel coupled training paradigm which exploited speech data with same text content. Our method gave huge gains in performance on heavy accents such as Indian.
