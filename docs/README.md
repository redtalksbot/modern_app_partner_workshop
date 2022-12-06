# Modern Applications Jumpstart Workshop

This workshop will walk you through common scenarios that an application developer may face as they transition an application from a monolith to microservices.

## Prerequisites

The following resources need to be installed on your laptop:

- [GitHub account](https://github.com)
- [Visual Studio Code](https://code.visualstudio.com/)
- [git](https://git-scm.com/downloads)
- [kubectl](https://kubernetes.io/docs/tasks/tools/)
- [jq](https://stedolan.github.io/jq/)
- [Hey](https://github.com/rakyll/hey) - HTTP Load testing utility. A drop-in replacement for ApacheBench.
- [GitHub CLI - optional](https://cli.github.com/)
- [cURL](https://curl.se/) - Usually pre-installed in Unix-based Operating systems, available when using Windows with WSL installed.
- NGINX Plus trial license - You will also need to request via SalesForce to obtain an NGINX Plus certificate, private key and JWT.
- Access to F5 Distributed Cloud

You will also need to [setup local authentication](https://docs.github.com/en/authentication) to GitHub.

**Note:** If you are taking this lab on a Windows system, it is **highly** recommended that you [Install Linux on Windows with WSL](https://docs.microsoft.com/en-us/windows/wsl/install).

## Lab: K8s Ingress

In this lab, you will install the NGINX Plus Ingress Controller into a K3s cluster.  You will also take a deep look at the VirtualServer Resource and some of the common configurations a modern application might need.

[Start K8s Ingress Lab](ingress/README.md)
