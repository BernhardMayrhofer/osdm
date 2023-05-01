# osdm

Test the osdm API

# Environment

[Jupyter/datascience-notebook](https://hub.docker.com/r/jupyter/datascience-notebook)

## Create Container from Docker Image

    $ docker pull jupyter/datascience-notebook
   
    $ docker container run -d -p 8888:8888 --name osdm jupyter/datascience-notebook
    
    # Get access URL
    $ sudo docker exec -it osdm jupyter server list
    
## Get repo

    $ git clone git@github.com:BernhardMayrhofer/osdm.git
    
## Create ssh key and push to repo

https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

    $ git remote set-url origin git@github.com:BernhardMayrhofer/osdm.git

## Manage Container

    $ docker container start osdm
    $ docker container stop osdm

# Credentials

Store your OSDM account credentials in your ~/.-env file:

    KEY_SECRET=XXX
    USERNAME=XXX
    PASSWORD=XXX

# Source

[OSDM.io](https://osdm.io/)
[UIC.org](https://uic.org/projects/osdm)
[Git](https://github.com/UnionInternationalCheminsdeFer/OSDM/tree/master/mock)