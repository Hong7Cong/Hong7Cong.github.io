---
title: "An Evaluation of Time Series Anomaly Detection in Computer Networks"
excerpt: "Image of network failures <br/><img src='/images/cisco.png'>"
collection: portfolio
---

One critical issue in any network systems is failure detection. Failures not only im-
pact the source network but also propagate through other communicating intermediate
and destination networks due to the butterfly effect, making root causing of failures
even more challenging. Therefore, the necessity to detect failures and anomalies in
computer networks is fundamental. Given the nature of computer networks, data is
received in a time-series format where each time-point has temporal dependencies on
others. As a result, time-series analysis stands out as a potential approach to deal
with the task of network anomaly detection. In this report, we conduct studies on
multivariate time series anomaly detection, varying from traditional machine learning
techniques to deep learning models. We show that the choice of models is not as impor-
tant as the choice of pre-processing techniques. Interestingly, non-linear normalization
can boost the performance of deep detectors by around 20% in terms of F1 score and
balance the preference of deep detectors for specific types of anomalies. We also study
the bias of anomaly types to deep detectors, time-performance trade-offs, shortage of
data, and effects of weakly labeled data on both synthetic and real-world datasets to
fill out the missing insights in the literature.

[Download paper here](http://hong7cong.github.io/files/MTSNetwork_ICOIN.pdf)

