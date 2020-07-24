
## Introduction
In this project we are deploying high available webserver using cloud formation .  

# Project Highlights
Application deployed in private subnet with complete secure and high availability using autoscalling and load balancing health checks to the target.
Application deployed with multiple availability zone in order to avoid any disaster. 
Application host can connect only bostion host with deployed in public subnet with high available autoscalling. 

## Instructions

```
a) create.bat udagramnetwork udagram_nw.yaml udagram_nw_param.json

```

```
b) create.bat udagramserver udagram_servers.yaml udagram_server_param.json 
```
