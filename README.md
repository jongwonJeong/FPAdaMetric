# FPAdaMetric: False-positive-aware Adaptive Metric Learning for Session-based Recommendation

Official PyTorch implementation of "FPAdaMetric: False-positive-aware Adaptive Metric Learning for Session-based Recommendation, AAAI, 2022" by Jongwon Jeong, Jeong Choi, Hyunsouk Cho, Sehee Chung at Knowledge AI, NLP Center, NCSOFT Corp.

## Abstract
Modern recommendation systems are mostly based on implicit feedback data which can be quite noisy because of false positives caused by many reasons, such as misclick or quick curiosity. Numerous collaborative filtering-based recommendation models have leveraged post-click user behavior (e.g.,skip) to identify false positives. False positives can be effectively involved in the model supervision as negative-like signals. Yet, they had not been considered in the previous
session-based recommendation systems (SBRs). False positives provide just as deleterious effects on the session-based user preferences as in CF-based recommendations. To resolve false positives in SBRs, we first introduce FP-Metric model by reformulating the objective of the session-based recommendation with false-positive constraints into metric learning regularization. In addition, we propose FP-AdaMetric by improving those metric-learning regularization terms using
the adaptive module for applying false-positive impact differently in the sequential pattern. We verify that FP-AdaMetric can improve several session-based recommendation models’ performances in terms of Hit Rate (HR), MRR, and NDCG on datasets from several domains including music, movie, and game. Furthermore, we show that the adaptive module plays a much more crucial role in FP-AdaMetric model than in other baselines.

## Code Information
The official code will be uploaded to [nc-ai Github](https://github.com/nc-ai) as soon as possible after getting the company's permission.
## Paper Information
We will upload the link to our paper after camera-ready uploading on AAAI 2022 is done.

## Citation
If you use our code, please cite the below. It will be uploaded after camera-ready is done.
