# Udacity course work - **Introduction to Machine Learning with Pytorch**

# Conclusion

## 1. Project results
 - Trained a transformer model from scratch to perform sentiment analysis on the IMDB (movie review) dataset.
 - Transformer neural networks can be customized for text classification by pooling token embeddings and adding a classifier.
 - Flow: load data --> tokenize --> dataloader --> transformer --> mean pooling --> classification --> logits --> loss --> back propagation --> validation accuracy.
 - Achieved validation accuracy of 85.72%

## 2. Key takeaways
 - Visualizing data first is a good way to gain insight for given data.
 - Data quality is critical. Initially, I had a wrong file path for negative review data and the accuracy stayed 50%, Loss around 69% after training. Fixing the file paths improved the result drastically.
 - I was able to increase the validation accuracy by adjusting parameters.
