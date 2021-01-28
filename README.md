# <em>TS-CP<sup>2</sup></em>
## Time Series Change Point Detection based on Contrastive Predictive Coding

# Abstract
Change Point Detection techniques aim to capture changes in trends and sequences in time-series data to describe the underlying behaviour of the system.
Detecting changes and anomalies in the web services, the trend of applications usage can provide valuable insights into the system. However, many existing approaches are done in a supervised manner, requiring well-labelled data. As the amount of data produced and captured by sensors are growing rapidly, it is getting harder and even impossible to annotate the data. Therefore, coming up with a self-supervised solution is a necessity these days. 
In this work, we propose <em>TS-CP<sup>2</sup></em> a novel self-supervised technique for temporal change point detection, based on representation learning with a Temporal Convolutional Network (TCN). To the best of our knowledge, our proposed method is the first method which employs Contrastive Learning for prediction with the aim of change point detection.
Through extensive evaluations, we demonstrate that our method outperforms multiple state-of-the-art change point detection and anomaly detection baselines, including those adopting the either unsupervised or semi-supervised approach. <em>TS-CP<sup>2</sup></em> is shown to improve both non-Deep learning- and Deep learning-based methods by 0.28 and 0.12 in terms of average F1-score across three datasets.
