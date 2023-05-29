# Fine Tuned Models
We utilize ALBERT and DistilBERT language models and fine-tune them with the UMD dataset to build the classifiers. 
For implementation, we employed the Huggingface library, an open-source library and data science platform that provides tools to build, train and deploy ML models.

The hyperparameters were selected based on a combination of intuition and systematic search. A grid search was conducted to explore a range of values for Learning Rate, Batch Size, Dropout Rate, and Maximum Sequence Length. The final hyperparameters used in our experiments were Learning Rate= 2e−5, Batch Size = 4, Dropout Rate = 0.1, and Maximum Sequence Length = 512. The values of these hyperparameters were selected based on their performance on the test set and our prior experience with similar tasks.
