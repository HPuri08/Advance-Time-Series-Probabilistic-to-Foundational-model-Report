# Time Series : Probabilistic to Foundational Models

Time series analysis is fundamental in many fields such as finance, health care, climate science, autonomous systems. This seminar discusses about three broad categories of time series model:explicit,implicit and task agnostic and foundational models.Explicit models include Interleaved Hidden Markov Model, Flow HMMs, Wavenet and DeepAR. These are probabilistic models and have strong assumptions about the data generation and have domain specific knowledge,these models also focus on the temporal dependencies explicitly. The implicit model includes BRITS and various Transformer based architectures (PatchTST, iTransformer) that focuses on temporal dependencies directly from data without any explicit assumption. The task and foundational models such as  BERT, MOIRAI, Visual Autoregressive Models, and Latent Diffusion Models highlight the potential to be generalized well to  other domains. Through comparative analysis of various models we analyze the trade offs in scalability , interpretability, etc. and model selection based on the task requirement and dataset characteristics.

# Predicting cellular responses to perturbation across diverse contexts with State

Cellular responses to perturbations are important for understanding biological mechanisms and
selecting drug targets. Many machine learning and deep learning approaches have been applied with
tremendous potential but some struggle with scalability and consistent performance while others
struggle to generalize to unobserved cellular contexts. In the seminar we discuss about STATE, a
transformer model that predicts perturbation effects while accounting for cellular heterogeneity within
and across experiments. It is trained using gene expression data from over 100 million perturbed
cells. We also discuss about Cell-Eval, a framework that measures the performance of the STATE.
We critically analyze the methodology and discuss about strengths and limitations of STATE.
