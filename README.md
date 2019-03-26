# docker-images
Repository contains docker configurations, images, and dockerfiles.

Download the rpm package for jdk version from Java dowloads page to your docker context
https://www.oracle.com/technetwork/es/java/javasebusiness/downloads/index.html

Execute command: 
docker build -f jdk1.8.0_131/Dockerfile --tag="centos/java:latest" .
