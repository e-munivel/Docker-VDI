## Docker VDI ![Taisun]

Docker VDI is an application for a Docker enabled device with an emphasis on providing a web based interface for managing a single server.

Taisun allows you to:

  - Deploy and manage web based virtual desktops.
  - Deploy Taisun specific stacks of applications
  - Browse available images on popular Docker repositories
  - Import a Docker project from any git repository and start developing on your choice of web based IDE or full Linux desktop
  - Spinup a developer container based on popular frameworks and work from a web based IDE

### QuickStart

On a Docker enabled host run the following command from cli:
```
sudo docker run --name taisun -d \
--restart always \
-p 3000:3000 \
-v /var/run/docker.sock:/var/run/docker.sock \
linuxserver/taisun:latest
```
Taisun will be available by accessing:

http://localhost:3000

