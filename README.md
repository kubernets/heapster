# heapster

github addr [https://github.com/kubernets/heapster](https://github.com/kubernets/heapster)

docker hub addr [https://hub.docker.com/u/kubernets](https://hub.docker.com/u/kubernets)

use shell script to pull docker image and replace origin tag

> wget https://github.com/kubernets/heapster/raw/master/get-heapster-image.sh

## Arch and Version

- [**amd64** v1.5.4](https://hub.docker.com/r/kubernets/heapster-amd64)

    > docker pull kubernets/heapster-amd64:v1.5.4

    > docker tag kubernets/heapster-amd64:v1.5.4 gcr.io/google-containers/heapster-amd64:v1.5.4 

    > docker rmi kubernets/heapster-amd64:v1.5.4
