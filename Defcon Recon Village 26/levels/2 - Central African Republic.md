# Challenge:
![Level 2 Screenshot](/images/Level2.png)

# Steps to Solve:
1. This is looking for a docker container based on "dock" and the free hint of "docker". The most well know repository is hub.docker.com. The other clue here is "our ship" so we'll search for reconvillage on that site. You'll find https://hub.docker.com/r/reconvillage/htop/
2. On you machine, you'll pull that containter: docker pull reconvillage/htop
3. The clue mentions "the past" so there's gotta be something about this image. We see that we have the latest version. Since we have pulled the image, we can use this command to view the history: docker image history reconvillage/htop. Voila! There's our flag - flag:a2b6140d13c52f30a8c139

![Level 2 Flag](images/RV26-02-Flag.png)
