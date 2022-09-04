## Naive Bayes from Scratch <hr>

<p align="center">
  <a href="https://github.com/rppradhan08/ml-models-from-scratch/tree/main/1.%20Linear%20Regression">
    <img src="https://github.com/rppradhan08/ml-models-from-scratch/blob/main/1.%20Linear%20Regression/lr_train.gif?raw=true" alt="Logo" width="500" align="center">
  </a>
</p>

The simplest solutions are usually the most powerful ones, and `Naïve Bayes` is a good example of that. Despite the advances in Machine Learning in the last years, it has proven to not only be simple but also fast, accurate, and reliable.

It has been successfully used for many purposes, but it works particularly well with natural language processing (NLP) problems.

Naïve Bayes is a probabilistic machine learning algorithm based on the Bayes Theorem, used in a wide variety of classification tasks. In this article, we will understand the Naïve Bayes algorithm and all essential concepts so that there is no room for doubts in understanding.

    NaiveBayes
        |
        |--fit() : This method is used to train the model parameters.
        |
        |--_predict() : This function performs prediction on a single row/input vector.
        |
        |--predict() : This generates estimate for the entire feature matrix (internally uses _predict).
        |
        |--_pdf() : This method calculates PDF for the provided input vector of specified class index.
