# osdm

Test the osdm API

# Environment

[Jupyter/datascience-notebook](https://hub.docker.com/r/jupyter/datascience-notebook)

# Create Container from Docker Image

    $ docker pull jupyter/datascience-notebook
   
    $ docker container run -d -p 8888:8888 --name osdm jupyter/datascience-notebook
    
    # Get access URL
    $ sudo docker exec -it osdm jupyter server list
    
# Get repo

    $ git clone git@github.com:BernhardMayrhofer/osdm.git

# Source

[OSDM.io](https://osdm.io/)
