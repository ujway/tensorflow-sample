# Tensorflow-sample
[Tensorflow](https://www.tensorflow.org/) Sample Repo.
This repo uses docker image based on tensorflow:night.

## Dependencies

- [Docker](https://docs.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)

## Setup
```sh
# clone
git clone https://github.com/ujway/tensorflow-sample.git
cd tensorflow-sample

# create a docker container
docker-compose up -d

# login
docker exec -it tensorflow bash
root@123456abcd:cd /var/src
root@123456abcd:python sample.py
root@123456abcd:jupyter notebook list
## 
## Currently running servers:
## http://localhost:8888/?token=1234567890asdfghjkl :: /notebooks

# Jupyter Usage
# open http://localhost:3789 on browser
# and input above token then enter
```
