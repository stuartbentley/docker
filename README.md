# docker

## python
Simple hello world python app taken from https://docs.docker.com/get-started/

### commands
docker build --tag=pythonapp .
docker run -p 4000:80 pythonapp
docker run -d -p 4000:80 pythonapp (run in background)
docker container ls (list apps)
docker container stop deb52db86e95 (Use container id)
