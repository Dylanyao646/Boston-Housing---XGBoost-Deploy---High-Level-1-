# Boston-Housing---XGBoost-Deploy---High-Level-1-
Using XGBoost in SageMaker (Deploy)
Deep Learning Nanodegree Program | Deployment

As an introduction to using SageMaker's High Level Python API we will look at a relatively simple problem. Namely, we will use the Boston Housing Dataset to predict the median value of a home in the area of Boston Mass.

The documentation for the high level API can be found on the ReadTheDocs page

General Outline
Typically, when using a notebook instance with SageMaker, you will proceed through the following steps. Of course, not every step will need to be done with each project. Also, there is quite a lot of room for variation in many of the steps, as you will see throughout these lessons.

1. Download or otherwise retrieve the data.
2. Process / Prepare the data.
3. Upload the processed data to S3.
4. Train a chosen model.
5. Test the trained model (typically using a batch transform job).
6. Deploy the trained model.
7. Use the deployed model.
In this notebook we will be skipping step 5, testing the model. We will still test the model but we will do so by first deploying the model and then sending the test data to the deployed model.
