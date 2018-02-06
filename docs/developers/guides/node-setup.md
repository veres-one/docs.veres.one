# Setting up a Veres One Node

This quick Developer Guide will walk you through setting up and running a
Veres One Node.

## Requirements

* [Docker](https://www.docker.com/community-edition)

## Download Docker

Download and modify the Docker compose file:

[veres-one-node.yaml](veres-one-node.yaml)

## Run docker-compose

Use the file you downloaded to run docker-compose:

```
> docker-compose -f veres-one-node.yaml up
```

Once the command above runs, you will be given a URL to connect to. Open
a web browser and go to that address.

## Setup your Veres One Node

To setup your Veres One Node, you must create a user account on the node.
The first account you create will be used to manage the node. When you are
ready to join the Network, click the "Join the Veres One Network" button.
