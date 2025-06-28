---
display_name: Node js development (only - no DB)
description: Provision Docker containers as Coder workspaces
icon: ../../../site/static/icon/nodejs.svg
maintainer_github: danielraab
verified: true
tags: [docker, container, node]
---

# Node JS Remote Development on Docker Containers

## Architecture

Everything takes place in one container (`codercom/enterprise-node:ubuntu`).

The following apps are available:

* VS Code Desktop
* code server (VS Code in Browser)
* PHP or Web Storm
* Button to start the webserver
* Open page in Browser
* Link to Repository (parameter of workspace)
* Open Terminal

![image](https://github.com/user-attachments/assets/7ae27f28-c8e8-434d-8fb0-6ec4b08fc9ab)
