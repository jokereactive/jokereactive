---
layout: page_project
name: Semi-Supervised Stance Detection in Tweets
intro:
teamsize: 3
teammembers: Aditya Agarwal, Tanmay Agarwal
guide:
course:
_url: 
projectimage: semitweet.png
weight: 0.9
category: Research
reference: http://sarthakahuja.org/public/docs/report_semitweet.png
code:
database: 
slides: 
poster: http://sarthakahuja.org/public/docs/poster_semitweet.pdf
demo: 
special:
technology: Latent Dirichlet Allocation, Word2Vec, Para2Vec, Semi-Supervised Learning, Representation Learning
period: January'19 - May'19
excerpt:
published:
patented: 
---
Collaborative robots are often designed to interact with people by predicting their intent. However, most work with collaborative robots acting on anticipated human intent, assumes intent remains constant throughout the task and cannot be altered by the collaborative robot partner. 

 - Implemented a heuristic-based semi-supervised learning approach, LDA2Vec (Moody CoNLL 2016) for stance detection that learns a coherent and informed embedding comparable to Para2Vec,  concurrently bolstering interpretability of topics by creating representations similar to those in Latent Dirichlet Allocation.
 - We conclude that adding unlabelled data vastly improves the performance of classifiers by ~6%
for LDA and ~20% for Para2Vec. Overall Para2Vec seems to perform better than the Vanilla LDA. While we are able to obtain a similar quality of topics with LDA2Vec as compared to LDA, the
generated embeddings do not reflect the expected classification quality compared to Para2Vec.