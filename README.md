# image-detection


## Overview

This repo utilizes the [InceptionV3](https://keras.io/api/applications/inceptionv3/) image recognition model alongside [Seldon Core](https://github.com/SeldonIO/seldon-core) in order to create a simple model serving demo. The notebook "model-explainability-serving.ipynb" initiates a gateway endpoint between the Jupyter Notebook and Seldon deployment, allowing users to send data to the model service and receive predictions. A local explainability algorithm is also implemented to better understand why the model is performing poorly.


## Outreach

This demo was presented at [DevConf.CZ](link) March 2021, "Beyond Inference: Bringing ML into Production." The video is available [here](https://www.youtube.com/watch?v=3ng-WcN_Th8) and slides avaiable [here](./slides). 

This talk explains the basics of model serving, why this is a relevant issue, how model serving offers relief for the data scientist/software engineer handoff, and know how to deploy a machine learning model with Seldon Core.

## Contact

Isabel Zimmerman
Data Science Intern -- Forward Deployed AI Engineering
github: [@isabelizimm](https://github.com/isabelizimm)
