# Memotag_sub
This proof-of-concept demonstrates an artificial intelligence-driven methodology for the early
detection of cognitive decline through the analysis of voice samples. By utilizing speech-to-text
technology such as Wav2Vec 1.0, in conjunction with natural language processing techniques like
semantic embedding using GloVe (Global Vectors for Word Representation), we successfully
extracted clinically pertinent speech features. These features include hesitation frequency, pitch
monotony, and semantic drift, all derived from anonymized voice recordings. The application of
Principal Component Analysis (PCA) for dimensionality reduction, paired with DBSCAN (Density-
Based Spatial Clustering of Applications with Noise) and Cosine Similarity as the distance metric,
enabled the identification of speech patterns frequently associated with cognitive stress, including
disorganized phrasing and difficulties in lexical retrieval. This pipeline presents a lightweight,
interpretable, and scalable framework suitable for the development of future clinical screening
instruments and the real-time monitoring of cognitive health.
