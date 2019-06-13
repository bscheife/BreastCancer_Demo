# BreastCancer_Demo
This notebook is a reference that goes along with a quick tutorial on selected classification algorithms that I gave at Insight Data Science. It's by no means intended to be exhaustive and it doesn't cover all possible classification methods. The notebook is not intended to explain the methodology behind each of the algorithms used (that's for the rest of the tutorial) but you could read about these here: https://medium.com/ml-research-lab/machine-learning-algorithm-overview-5816a2e6303

The goal of this demo is to use the public UCI Wisconsin Breast Cancer dataset to develop a model that can classify cancerous breast tumour as benign or malignant. As we'll see, this dataset isn't actually all that great for highlighting the strengths and weaknesses of ML algorithms, because the data segragate quite cleanly into two classes. Our predictive capability on the test set (which was excluded from the training) is above 90% or so regardless of the algorithm or the degree of overfitting. A more difficult classification problem, where the two distinct classes are more difficult to distinguish from each other, would probably be more instructive. It's on the to-do list...

The website where I got the data is: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Original)

