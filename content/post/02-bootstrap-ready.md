---
title: Installation Tool Ready
date: 2018-10-15
tags: ["bootstrap","haas"]
---

The installation application is now ready, called "haas-bootstrap". This will step through the setup of the various containers required to get Homelab as a Service working with no manual intervention required. Just run the command on the front page of this website and browse to localhost:3010 and you can step through the installation. It currently only supports running on Docker for Mac/Windows and also supports running the node app locally, ie, not in a container.

More work to support other deployment types will be done in the future, such as supporting docker swarm, Kubernetes and docker-compose. I'm also looking to reduce the size of the bootstrap container as I was having troubles with the alpine images and nodegit so I reverted to the larger node base container.

The final bit of work will allow you to migrate the database from an existing installation, ie. you want to move from a local setup into a Kubernetes cluster.