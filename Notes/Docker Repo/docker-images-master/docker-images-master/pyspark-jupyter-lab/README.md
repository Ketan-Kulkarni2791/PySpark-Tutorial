# PySpark Jupyter Lab Notebook - Python v3.10

Jupyter Lab Notebook with root access.
EaseWithApacheSpark notebooks provided to start with.

### To build image from the Dockerfile:
    docker build --tag ketanpyspark/pyspark-jupyter-lab .

### To create container from image
    docker run -d -p 8888:8888 -p 4040:4040 --name jupyter-lab ketanpyspark/pyspark-jupyter-lab

> [!CAUTION]
> In case you want to make setup easy, follow the below step.

## In case you are still not able to setup, just pull the image from docker hub
    docker pull ketanpyspark/pyspark-jupyter-lab
