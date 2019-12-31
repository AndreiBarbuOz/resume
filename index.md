---
layout: default
title: Andrei Barbu
---

Computer scientist, RPA Developer, Software engineer, Cloud practitioner

Interested in good practices, correlations between project organization and long term success, understanding the differentiators which make a project work over vast expanses of time and multiple iterations.

## Projects and interests

### RPA demo scalability

A project comprised of multiple repos, with the aim of providing a demo-ready virtual machine containing all the necessary software for showcasing UiPath technology interacting with target applications. The project made use of [Packer](https://www.packer.io/) for the creation of the actual managed image, and [Ansible](https://www.ansible.com/) for the configuration management and application deployment. 

The first cloud implementation was on [Azure](https://azure.microsoft.com/en-us/) and it was comprised of 3 repos:
- the [deployment container](https://github.com/AndreiBarbuOz/uipath-demo-image-deploy), consisting of an [Azure pipeline](https://azure.microsoft.com/en-au/services/devops/pipelines/) to build the Docker container used in the actual image build
- the actual [image](https://github.com/AndreiBarbuOz/uipath-demo-image) pipeline, building the Azure managed image, which is the base for all demo VM's. It is a build pipeline, which takes the declarative configuration of the desired state, and creates the image.
- the [demo environment](https://github.com/AndreiBarbuOz/uipath-demo-environment), a set of ARM templates, creating the infrastructure needed and then actually deploying the demo VM's based on the image created already.


### Testing automation demo environment

Ongoing project aimed at creating a demo environment for the UiPath Testing Solution. A full stack project comprising an OpenAPI specified microservice suite developed using Flask and hosted on K8s, coupled with an Angular front end and a native Windows app. 


### Continuous integration and delivery in RPA

An initiative to build a model translating practices from other fields of computer science into RPA space regarding continuous integration and delivery of RPA projects. 

### RPA good practices

A list of practices which should followed when developing RPA projects. The project is ongoing and the recommendations can be found [here](https://github.com/AndreiBarbuOz/uipath-good-practices), while there is also an [UiPath project](https://github.com/AndreiBarbuOz/uipath-doc-manipulation) showcasing the ideas in a sample project. Forks and PRs are welcomed.

### UiPath Orchestrator python client library

Initiated a client libarary for [UiPath Orchestrator API](https://docs.uipath.com/orchestrator/reference) implemented in Python. WIP

## Occupation

`2018 - present`
__UiPath__, Melbourne

RPA developer and cloud engineer, part of the presales department. During the day I:
- perform demos
- guide customers and partners through their RPA journey
- implement proof of concepts and pilots
- architect solutions
- assess infrastructure setup

During the night:
- develop infrastructure as code projects to showcase UiPath usecases
- architect and then build environments for proove concepts and usecases for RPA
- develop templates and good practices samples around the use of UiPath

`2018`
__Two Bulls__, Melbourne

Backend Python developer, using a wide range of products from AWS to deliver information coming through IoT Core. Created high level architecture, implemented the CI/CD pipeline and the whole CfN templates to create the whole environment. Implementation included Lambda functions, Docker, SQS and API Gateway, everything being described as Code.


`2017`
__CPT Global__, Melbourne

Python developer using Flask to deploy an API with a microservice architecture on GCP infrastructure. The API would serve sports (AFL) results and statistics, as well as sports outcome predictions. 

Implemented the ML model using Scikit learn, testing a number of models and parameters, performing such activities as:
- dimentionality reduction
- hyper parameter tuning
- high cardinality features identification


`2009 - 2016`
__The vegetable basket__, Bucharest

`2007 - 2009`
__Alvarion__, Bucharest

Old school programming in C of an embedded device, on a low power processor running a stripped down version of a real-time OS from *back in the day*.

Interacted with the bare metal, moved packets from FPGA and DSP queues, implemented efficient algorithms without the use of libraries. 

## Education

`2017`
__RMIT University__, Melbourne

`2002 - 2007`
__"Politehnica" University__, Bucharest

`2005`
__Katholieke Universiteit__, Leuven

`2004`
__Uppsala universitet__, Uppsala

`1998 - 2002`
__National Computer Science college "Tudor Vianu"__, Bucharest


## Free time

I get away from my online work by playing blitz *chess* ...online and grand strategy games ...online. I also do hiking, boxing and ocasionally I deadlift heavy things.


