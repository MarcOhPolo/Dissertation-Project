This dissertation presents a comprehensive evaluation of machine learning and anomaly
detection models for malware classification across varying system contexts, including DNS
traffic, hardware data, and multi-device local networks. Three datasets are used to represent
these contexts. The goal is to develop predictive models capable of accurately identifying
malicious programs using diverse types of data, and to analyse how these models perform in
different scenarios.
The research focuses on how model performance varies across contexts and highlights the
strengths and weaknesses of three models: Random Forest, Naïve Bayes, and Gaussian Mixture
Models (GMM). This dissertation details the tools and techniques used to create, train, and test
the models.
It then discusses the methodology and structure of the implementation, providing examples of
each step in the process. Issues and risks encountered during implementation are also
described, along with how each was addressed or resolved. Once results are presented, the
discussion covers how these results were generated and explains the choice of evaluation
metrics. The metrics recorded include overall accuracy (%), F1 score (%), and the time taken
to train and test the models (in seconds).
The findings demonstrate that model performance varies significantly depending on the system
context. Random Forest delivered the highest accuracy and F1 scores, though with longer
computation times. Naïve Bayes offered faster results with reasonable accuracy. GMM showed
limited effectiveness and relatively slow computation across all scenarios.
By comparing these models across DNS, hardware, and local network datasets, this dissertation
provides insights into their practical applicability and trade-offs. In addition to evaluating
technical performance, the study proposes directions for future research, building on the
insights gained in this project.
