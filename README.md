# Phase2 docker-diffy

> Docker image for using the diffy cli tool.

This Docker image adds the [diffy cli](https://github.com/DiffyWebsite/diffy-cli) tool to the base `alpine:latest` image.

## Image generation

* To generate new images for the latest diffy cli version:
* * Go to the [diffy cli repo](https://github.com/DiffyWebsite/diffy-cli) and find the latest version.
* * Update the `src/Dockerfile` and set the DIFFY_VERSION variable to the desired version.
* * Commit and tag the main branch with `v` followed by the version number: ex `v0.1.22`
* * Push the updates and tag upstream.

## Security Reports

Please email outrigger@phase2technology.com with security concerns.

## Maintainers

[![Phase2 Logo](https://s3.amazonaws.com/phase2.public/logos/phase2-logo.png)](https://www.phase2technology.com)