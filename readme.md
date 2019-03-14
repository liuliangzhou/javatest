**Build**

`$ sudo docker run -it --rm -v "$PWD":/usr/src/mymaven:rw -v /tmp/docker-m2cache:/root/.m2:rw -w /usr/src/mymaven maven:3-jdk-8 mvn clean package`

or 

`$ sh build.sh`

**Run**

`$ sudo docker build .`

or 

`$ sh run.sh`
