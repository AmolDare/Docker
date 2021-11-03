# Docker
Docker is a Containerization Platform which allows us to containerize an application/software (called as Docker Image) & also lets you run Containerized application/software

Docker Engine-
Docker is a client-server application. You must have both parts for running a Docker application on your computer. This client-server tandem is called docker engine.
The docker client is just a CLI tool to make requests against a REST API, which is responsible for interacting with the docker daemon or dockerd. dockerd will deal with the operative system to ensure the proper behaviour for the containers.

#Docker Image
A package which consists of an application/software with all its dependencies to run, Called as Docker Image

Docker Image will have a base layer of minimal OS in it always, on top of OS layer we install software & its dependenci es.

A Docker image is built up from a series of layers. Each layer represents an instruction that we run.

A Docker image is a lightweight, standalone, executable package of software that includes everything needed to run an a pplication: code, runtime, system tools, system libraries and settings


#what is Docker Container ?
A container is runtime instance of a Docker Image

Namespaces
Docker uses a technology called namespaces to provide the isolated workspace called the container. When you run a container, Docker creates a set of namespaces for that container.
These namespaces provide a layer of isolation. Each aspect of a container runs in a separate namespace and its access is limited to that namespace.

