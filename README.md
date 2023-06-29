# end-to-end-ml-system-aws-sagemaker

A complete ML pipeline is built on the [Amazon SageMaker studio].
The pipeline comprises data pre-processing, training and hyperparameter
tuning, deploying and monitoring.

The main difference of ML in production is all data science related jobs are
now done at scale. The pre-processing done on modelling step should be done
exactly the same on the production as well. Thus, the pre-processing pipeline
should be saved for future tasks on production step.

This repository paves a framework template to develop a production ready
ML system that stores data in amazon S3, train and tune models, and monitor
in system that are already in production.
