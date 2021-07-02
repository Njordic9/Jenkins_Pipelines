# Jenkins_Pipelines
Python and Jenkins Files for Different types of Pipelines.

## Table Contents

This repository contains:

[A small subset](https://github.com/Njordic9/Jenkins_Pipelines) of Groovy files used for Jenkins Pipelines.

1. [JenkinsPipeline1](#jenkinspipeline1) use case.

2.

## JenkinsPipeline1

* This pipeline asks the user to enter in two inputs (in this case, Firewall IP address and Email address).  
* The pipeline will go through and run the python script attached to the pipeline.  In this usecase, it's reaching out to the IP address the user input and retrieving all the NAT's that have no translations.
* It'll then compile the output and Email the report out.

### Pre-req Installation

* Scripting language of your choice.

#### Software Dependencies

* Jenkins and Groovy

#### Badge

Standard-Readme compliance badge.

[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

## Maintainers

[@Njordic9](https://github.com/Njordic9).
