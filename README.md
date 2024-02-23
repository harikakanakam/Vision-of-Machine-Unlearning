# The Vision of Machine Unlearning

Machine unlearning has come to light in recent times
with a focus on solving user privacy regulations. Researchers are
experimenting with a lot of techniques to effectively remove the
impact of the user’s information on the trained models based on
their requests. Though retraining the model from scratch for the
remaining dataset would be the gold standard, it would incur a huge
cost in terms of computational capabilities and the runtime in a
real-time setting. A lot of unlearning techniques have been evolved
by researchers to achieve not just high unlearning performance but
also retain the model accuracy. This research work is an attempt to
contribute to the field of machine unlearning by implementing different
techniques like the forget-remember cycle, self-contrastive adversarial
learning, and stochastic re-initialization. We evaluated our models by
injecting Membership Inference Attacks into the unlearned model and
reported the scores of the same as forget quality. Our top-performing
models have achieved a forget quality of 0.74 on the CIFAR10
dataset as compared to the baseline model’s forget quality which
sticks around 0.63. We have conducted extensive experimentation and
troubleshooting to come up with different models that achieved decent
forget quality scores, all of which have been reported in the later
sections of the paper.
