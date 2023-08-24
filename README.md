# Installation
docker build -t myjenkins-blueocean:2.332.3-1 .

#IF you are having problems building the image yourself, you can pull from my registry and rename it to `myjenkins-blueocean:2.332.3-1`

docker pull devopsjourney1/jenkins-blueocean:2.332.3-1 && docker tag devopsjourney1/jenkins-blueocean:2.332.3-1 myjenkins-blueocean:2.332.3-1
