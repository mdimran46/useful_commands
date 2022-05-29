##Docker basic commands
- docker –version[^1]
- docker pull <image name>[^2]
- docker run[^3]
  > docker run -it -d <image name>
- docker ps[^4]
- docker ps -a[^5]
- docker exec[^6]
  > docker exec -it <container id> bash
- docker stop <container id>[^7]
- docker kill <container id>[^8]
- docker commit[^9]
  > docker commit <conatainer id> <username/imagename>
- docker login[^10]
- docker push[^11]
  > docker push <username/image name>
- docker images[^12]
- docker rm <container id>[^13]
- docker rmi <image-id>[^14]
- docker build <path to docker file>[^15]

####Description:
[^1]: This command is used to get the currently installed version of docker
[^2]: This command is used to pull images from the docker repository [DockerHub](https://hub.docker.com/)
[^3]: This command is used to create a container from an image
[^4]: This command is used to list the running containers
[^5]: This command is used to show all the running and exited containers
[^6]: This command is used to access the running container
[^7]: This command stops a running container
[^8]: This command kills the container by stopping its execution immediately. The difference between ‘docker kill’ and ‘docker stop’ is that ‘docker stop’ gives the container time to shutdown gracefully, in situations when it is taking too much time for getting the container to stop, one can opt to kill it
[^9]: This command creates a new image of an edited container on the local system
[^10]: This command is used to login to the docker hub repository
[^11]: This command is used to push an image to the docker hub repository
[^12]: This command lists all the locally stored docker images
[^13]: This command is used to delete a stopped container
[^14]: This command is used to delete an image from local storage
[^15]: This command is used to build an image from a specified docker file


