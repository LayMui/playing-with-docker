# docker build 

To build the docker image using the definitions in dockerfile using docker build command. 
```
cd playing-with-docker
docker build .
```
Successfully built 34b1fd0b18a9

After the docker build process, you have built an image that can run 
the nodejs app

After the docker build, you can run the container using the command
docker run -p 3000:3000 -it 34b1fd0b18a9

hit the url localhost:3000 to see the node app running

to stop the container

docker stop <containerID>
