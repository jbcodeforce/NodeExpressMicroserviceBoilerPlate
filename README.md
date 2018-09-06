# Node Express Microservice BoilerPlate
This is my own boiler plate to start a project using nodejs and expressjs for a micro service implementation. It is based on IBM cloud starting code, but add explanations in code and other goodies I have to use over time.

## Table of contents
* [Summary](#summary)
* [Requirements](#requirements)
* [Project files](#project-files-and-structure)
* [Build and run](#build-and-run)

## Summary
This boiler plate is a The Backend for Frontend pattern to expose REST api. It helps you focus on exposing business data and services in a form that matches the user interaction requirements.

## Requirements
You need nodejs, npm installed.

## Project files and structure
* Manifest.yml is for deploying to IBM Cloud / Bluemix using Cloud foundry
* package.json	Metadata file for nodejs dependencies and command definitions for `npm run`
* cli-config.yml	CLI configuration options
* Dockerfile	Dockerfile for ibmcloud dev run, ibmcloud dev deploy, and docker commands
* Dockerfile-tools	Dockerfile for ibmcloud dev build and ibmcloud dev test
* docker-compose.yml	App service configuration for Docker Compose
* webpack.config.js	Webpack configuration for build related information
* .bluemix includes scripts and pipeline files for bluemix toolchain.
* .chart 

## How to use this boilerplate

## Build and Run
