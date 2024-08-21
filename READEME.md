## [sec02 - 23]
### "WORKDIR" means make directory inside of container
### "CMD" array divided by space

## ["docker run -it ..."]
### "-it" option is interactive. if option is added, you want to connect inside of container

## How to get more Simple Node Container
### - "docker run node" (if doesn't have locally, pull from docker hub)

### - "docker build -t [이미지명] ."
### - "docker build -t tom-node-image ."

### - "docker run -p 3000:80 --name [컨테이너명] [언어]" I'm not sure whether 언어 or not
### - "docker run -p 3000:80 --name tom-node-container node"

### done
