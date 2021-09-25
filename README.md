# Inspect-Remove-and-Prune-an-Image-Docker

Steps to Inspect, Remove, and Prune an Image-

```

1. Use the following command to pull the nginx image from Docker Hub:
$ sudo docker pull nginx:latest

2. Use the following command to inspect a Docker image:
$ sudo docker image inspect nginx:latest

3. se the following command to list all the running images:
$ sudo docker images

4. Use the following command to remove an image:
$ sudo docker image rm IMAGE_ID

5. Use the following command to force remove an image:
$ sudo docker image rm --force IMAGE_ID

6. Use the following command to remove all untagged images:
$ sudo docker image prune --all

```
