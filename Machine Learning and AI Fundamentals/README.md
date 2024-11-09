# Machine Learning and AI Fundamentals

Machine learning can be divided into two main categories: supervised and unsupervised learning. In supervised learning, the algorithm learns from labeled data, while in unsupervised learning, the algorithm identifies patterns from unlabeled data.

In the spirit of this course, we will be learning just enough to know what questions to ask next.

Please feel free to explore the topics in more depth on your own!

## Supervised Learning

Supervised learning is further divided into regression and classification tasks. In regression, the algorithm predicts a continuous value, while in classification, the algorithm predicts a discrete value.

To get started, we will implement a simple linear regression model using the [Diabetes dataset](https://scikit-learn.org/stable/datasets/toy_dataset.html#diabetes-dataset).

[Get started here!](./Start/Diabetes%20Regression.ipynb)

## Unsupervised Learning

Unsupervised learning is used to identify patterns in data without any prior knowledge. Clustering and dimensionality reduction are common unsupervised learning techniques.

Let's start with a simple example of clustering using the [Iris dataset](https://en.wikipedia.org/wiki/Iris_flower_data_set). Note: the Iris dataset is a classic <u>labeled</u> (remember, think supervised) dataset, but we will ignore the labels for this exercise to treat it as an unsupervised learning problem.

[Get started here!](./Start/Iris%20Clustering.ipynb)

We'll implement k-means and hierarchical clustering algorithms to cluster the Iris dataset.

Dimensionality reduction is another unsupervised learning technique that is used to reduce the number of features in complex data. We'll use [The Cancer Genome Atlas (TCGA) dataset](https://www.cancer.gov/about-nci/organization/ccg/research/structural-genomics/tcga) to demonstrate principal component analysis (PCA) and t-distributed stochastic neighbor embedding (t-SNE) techniques.

[Get started here!](./Start/Cancer%20Dimensionality%20Reduction.ipynb)

## Climate AI Models

Two additional topics that are particularly relevant to climate ML domain are deep learning for computer vision and time series forecasting.

### Deep Learning for Computer Vision

Deep learning models, such as convolutional neural networks (CNNs) and recurrent neural networks (RNNs), have been widely used in computer vision and natural language processing tasks. We will explore more applications of computer vision in the Earth observation chapter.

For now, let's set up an image recognition model to classify numbers from the [MNIST dataset](https://en.wikipedia.org/wiki/MNIST_database).

[Get started here!](./Start/MNIST%20Computer%20Vision.ipynb)

### Time Series Forecasting for Climate Data

Time series forecasting models, such as ARIMA, LSTMs, and transformers, are essential for analyzing temporal data, such as climate and weather data.

Let's set up a time series forecasting model using the Daily Minimum Temperatures in Melbourne dataset [(raw data)](https://raw.githubusercontent.com/jbrownlee/Datasets/master/daily-min-temperatures.csv).

[Get started here!](./Start/Melbourne%20Forecasting.ipynb)

<!-- https://rstudio-pubs-static.s3.amazonaws.com/780805_e5204cea11a44fa99f09bc4cc8816593.html -->
