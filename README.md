## Build docker image

`docker build -t ml-notebooks-docker .`

## Run image

`docker run -it -p 8888:8888 -v $(pwd)/notebooks:/home/jovyan/ ml-notebooks-docker`


## Sources
- https://becominghuman.ai/simple-neural-network-on-mnist-handwritten-digit-dataset-61e47702ed25
