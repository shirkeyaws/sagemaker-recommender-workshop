# Amazon SageMaker Recommender Workshop

## Agenda

- {0.75} Introduction
    - {0.5} Overview of ML workflow -> decks/Recommender_Workshop_01_Introduction.pptx
    - {0.25} MovieLens data intro -> notebooks/01_exploring_data.ipynb
        - preflight: CFN template check -> cfn_setup.yaml
        - launch individual notebook instances
            - what sizes?
        - clone repo -> http://bit.ly/2wkaV0N (this repo)
- [0.5] Unsupervised ML
    - concepts
    - hands-on
- [0.25] **Break**
- [1] Recommendation Engine
    - [0.25] concepts
    - [0.75] hands-on
        - show movie recommender website: http://sagemaker-nab-demo.s3-website-us-west-2.amazonaws.com/
        - clone repo to individual notebook instances
        - run all at beginning of workshop
        - TBD: perform training locally?
        - during training: discussion of underlying mechanisms for SageMaker (Batch, ECR, etc)

- [0.5] Hyperparameter Optimization (PPT+Demo)
    - overview
    - demo w/ XGBoost
- [0.25] Wrap-up (PPT)
    - Other resources
    - Next steps
    

## References

- https://grouplens.org/datasets/movielens/
- https://medium.com/@julsimon/building-a-movie-recommender-with-factorization-machines-on-amazon-sagemaker-cedbfc8c93d8
- http://sagemaker-nab-demo.s3-website-us-west-2.amazonaws.com/
- https://sagemaker.readthedocs.io/en/latest/factorization_machines.html