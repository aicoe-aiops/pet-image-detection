# Image Detection Demo

_A brief introduction to model serving with Seldon using the InceptionV3 image recognition model._

After a data scientist has created and trained a model, the next step is putting the model into production. Model serving deploys machine learning models as microservices that can interact easily with other pieces of a larger intelligent application. 

This repo utilizes the [InceptionV3](https://keras.io/api/applications/inceptionv3/) image recognition model alongside [Seldon Core](https://github.com/SeldonIO/seldon-core) in order to create a simple model serving demo. The notebook `model-explainability.ipynb` initiates a gateway endpoint between the Jupyter Notebook and Seldon deployment, allowing users to send data to the model service and receive predictions. A local explainability algorithm is also implemented to better understand how the model is making its predictions. 

**[Get Started](docs/get-started.md)**

**[Project Content](docs/content.md)**

**[How to Contribute](docs/how-to-contribute.md)**

## Contact

This project is maintained by the AIOps teams in the AI Center of Excellence within the Office of the CTO at Red Hat. For more information, reach out to us at aicoe-aiops@redhat.com.
