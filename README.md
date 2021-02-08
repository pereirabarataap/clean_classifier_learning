# DENOISE

Noise in data is a pervasive concern, with causes ranging from human entry errors to flawed automated detection tools.
When used to learn a classifier, noisy samples ---where class labels and feature values may be corrupted--- can seriously deteriorate the resulting classifier performance.

In this paper we propose Denoise, a unified method to perform classifier learning from noisy samples that leverages noise detection and sample weighting techniques.
It is particularly applicable to the situation in which label noise and feature noise may share dependencies.
The proposed approach consists of learning a noise-resilient classifier through a log-odds sample weighting strategy, in which the weights are derived from the noisy instances in a label noise detection step.

We empirically validate the performance of our method in a controlled scenario where noise is artificially injected into a diverse set of datasets.
Different parameterised configurations of label noise and feature noise proportions are extensively tested against current state-of-the-art methods from the fields of classifier learning under noisy conditions and label noise detection.
Results over ten datasets show that our approach consistently outperforms the state-of-the-art with respect to both learning from noisy data and noise detection.
