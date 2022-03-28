# Unsupervised-Sentiment-Analysis
Implemented sentiment analysis model for movie reviews by extraction of TF-IDF features and Gaussian Mixture Models (GMMs) from scratch in python.
Dataset used: http : //www.leap.ee.iisc.ac.in/sriram/teaching/M LSP 22/assignments/speechM usicData.tar.gz

Observation:
We notice that reviews for the two classes are quite overlapped in the latent space on which the data has been projected. Thus, it is expected that the model will not perform well if the classification is to be performed based on just the posterior probabilities of the Gaussians. This fact is quite evident from the plots shown above where we observe that the Gaussians at least in the first two dimensional space of PCA is learning to mimic the data distribution but cannot differentiate between the two.

