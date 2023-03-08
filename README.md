https://hub.docker.com/repository/docker/a1kot/docker-lab/general


D:\NODE-JS-Docker_Lab> docker build . -t a1kot/docker-lab     
docker build - a command to build docker image
. - path
-t - tags an image
alkot/docker-lab - name of the image

D:\NODE-JS-Docker_Lab> docker run -m 512m --cpus=2 -p 49160:8080 -d a1kot/docker-lab
docker build - a command to run docker image in a container
-m 512m - a command to limit memory usage to 512 megabytes
--cpus=2 - a flag that states that number of CPUs involved equals 2
-p 49160:8080 - a command to specify on which port we can access the app
-d - run container in background and print container ID
a1kot/docker-lab - name of the image
