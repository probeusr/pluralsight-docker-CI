# Test app for Pluralsight course

This is a quick and dirty test node.js app cobbled together for the purposes of demonstrating a basic CI/CD workflow with Docker Hub for a Pluralsight video training course..

## Instructions for use

All of the files included in the .zip file (available to Plus subscribers) should be unzipped into a new directory.

Initializing a Git repo and making a remote of it on GitHub are explained in Module 2 of the course.

## Adjustments on CircleCi
### New Directory Structure
circle.yml file has been moved into new directory and dramatically enhanced in order to be comlpiant with cicleci V2 ;)

### CircleCi Workflow
With V2 CircleCi introduced workflow this enhancement pickes up a lot of Jenkins functionality and also Docker Image functionalites

### CircleCi Dockerhub linking
Environment Variable adjustment
See this URL https://discuss.circleci.com/t/successful-builds-not-triggering-docker-cloud-build-trigger-returning-curl-400-bad-request/15569


