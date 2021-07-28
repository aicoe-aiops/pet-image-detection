# Table of Contents

This project repo consists of the following:

- [Image Explainability notebook](../notebooks/image-explainability.ipynb)
- [Seldon Custom Resource Definition](../image-classifier.yaml)

Along with resources available in this repository, a version of this demo was presented at [DevConf.CZ](https://www.devconf.info/cz/) March 2021, "Beyond Inference: Bringing ML into Production." The video is available [here](https://www.youtube.com/watch?v=3ng-WcN_Th8) and slides avaiable [here](../slides). 

To learn how to use this demo, look at the "Getting Started" guide [here](get-started.md).

## Image explainabilty notebook

The notebook showcases how to set up a connection between a machine learning model deployed with [Seldon Core](https://github.com/SeldonIO/seldon-core) and a Jupyter notebook. It also investigates how models make decisions with an explainability algorithm.

[Notebook](../notebooks/image-explainability.ipynb)

## Seldon Custom Resource Definition

In order to deploy the model in your own Kubernetes environment, you can use the Custom Resource Definition (CRD) provided. This step is not necessary for those using the Operate First environment.

[Custom Resource Definition](../image-classifier.yaml)

