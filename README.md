# assignment_17.1

Practical Application Assignment 17.1

This repo contains the Jupiter Notebook for Assignment 17-1 which can be found here: https://github.com/rcolcord/assignment_17.1/blob/main/prompt_III.ipynb

Findings
When testing on accuracy, all four models performed comparably well, with Logistic Regression ever-so-slightly better than the others. However, when scoring on precision, Decision Trees performed the best, with Logistic Regression performing comparably well.
In terms of training times, SVM took several orders of magnitude longer than the other three models. Times were consistent across the various training iterations. SVM was not one of the performant models, so we can be relieved to ignore this massive drawback of the model. For our two performant models, Logistic Regression took about twice as long to train as Decision Trees. However, both training times were very short, so unless we have major resource constraints, this shouldn't be a meaningful consideration.

Next Steps and Recommedations
I would recommend that the Decision Tree model be developed further, perhaps by testing more hyperparameters. Importantly, the model should be examined to glean insights about the specific features that are important in determining which customers will subscribe. This is one of the great benefits of Decision Tree models, they are very logically interpretable. Given time, I would also further develop the Logistic Regression model, which also provides insight about which input features are most important via the feature coefficients. I would compare the two models for any common conclusions about which features seem most relevant, as well.
