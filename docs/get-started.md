# Get Started

This project is made to walk users through what model serving is, and how it fits into the machine learning workflow. This notebook will demonstrate how to connect to a model with Seldon.


## Launch Project and Run Notebooks via JupyterHub

To make the notebooks reproducible, we have deployed containerized notebook images on the public [JupyterHub][jupyterhub] instance on the [Massachusetts Open Cloud][moc]. You can get access to a Jupyter environment using your Google account! To do so, please follow the steps below:

1. Visit the Operate First [JupyterHub][jupyterhub]
2. Click on `Log in with moc-sso` and sign in through Google.
3. On the spawner page, select `Image Detection` for notebook image, `Large` for container size, and then click `Start server` to spawn your server.
4. Once your server has spawned, you should see a directory titled `pet-image-detection-<current-timestamp>`. All the notebooks should be available inside the `notebooks` directory in it for you to explore.


## More resources

If you are looking for more, a version of this demo was presented at [DevConf.CZ][devconfcz] March 2021, "Beyond Inference: Bringing ML into Production." The video is available [here][video] and slides avaiable [here][slides]. This talk explains the basics of model serving, why this is a relevant issue, how model serving offers relief for the data scientist/software engineer handoff, and know how to deploy a machine learning model with Seldon Core.


[jupyterhub]: https://jupyterhub-opf-jupyterhub.apps.zero.massopen.cloud
[moc]: https://massopen.cloud/
[devconfcz]: https://www.devconf.info/cz/
[video]: https://www.youtube.com/watch?v=3ng-WcN_Th8
[slides]: https://github.com/aicoe-aiops/pet-image-detection/tree/main/slides
