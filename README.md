# Adaboost
AdaBoost stands for Adaptive Boosting. It is an ensemble learning technique used to improve the performance of weak classifiers by combining them into a strong classifier.

# How AdaBoost Works (Intuition):

Start with all training samples having equal weights.

Train a weak classifier (e.g., a shallow decision tree).

Evaluate the classifier:

If a sample is misclassified, increase its weight.

If correctly classified, decrease its weight.

Train the next classifier, focusing more on the misclassified samples.

Repeat steps 2–4 for a set number of models (estimators).

Combine all the weak classifiers into a final strong prediction by weighted voting.
