# Vulnado - Intentionally Vulnerable Java Application - DevSecOps Labs

This application and exercises will take you through some of the OWASP top 10 Vulnerabilities and practice DevSecOps Hands-ON.

## Up and running

1. Install Docker for [MacOS](https://hub.docker.com/editions/community/docker-ce-desktop-mac) or [Windows](https://hub.docker.com/editions/community/docker-ce-desktop-windows). You'll need to create a Docker account if you don't already have one.
2. `git clone git://github.com/ScaleSec/vulnado`
3. `cd vulnado`
4. `docker-compose up`
5. Open a browser and navigate to the client to make sure it's working: [http://localhost:1337](http://localhost:1337)
6. Then back in your terminal verify you have connection to your API server: `nc -vz localhost 8080`

## Exercises

1. DevOps Pipelines - Build & Test with Maven
2. DevSecOps - Integrating SCA, SAST, DAST, Container Scans & IaC Scans


