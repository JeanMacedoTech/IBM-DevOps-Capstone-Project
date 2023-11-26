# IBM DevOps Capstone Project | IBM DevOps And Software Engineering Specialization Course

![Build Status](https://github.com/JeanMacedoTech/devops-capstone-project/actions/workflows/ci-build.yaml/badge.svg)

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Python 3.9](https://img.shields.io/badge/Python-3.9-green.svg)](https://shields.io/)

This repository contains the code for the final project, part of the [**IBM DevOps and Software Engineering Professional Certificate**](https://www.coursera.org/professional-certificates/devops-and-software-engineering)

## Project Details

In this project, I had the opportunity of creating a full CI/CD pipeline, deploying a basic Python-Flask RESTful API application coded from scratch, in a microservice architecture format, inside of an OpenShift cluster in the cloud.

The application code was written following Test and Behavior-driven Development approaches, where unit and integration tests lead the creation of the app, using Nose as the unit test Python library, along with color spec and 95% code coverage, and Flake8 for code linting and overall code quality.

Application's technical debt and enhancements were managed with a ZenHub's Kanban board, following good Agile Development philosophy and SCRUM methodology.

Git Actions were used for the automation of the CI workflow on commit to Main or Pull Requests.

Tekton CD and an OpenShift Pipeline were used for the automation of the CD workflow, deploying the newly built Docker image to the OpenShift cluster inside the IBM Cloud.

## Instructor

[John Rofrano](https://www.coursera.org/instructor/johnrofrano), Senior Technical Staff Member, DevOps Champion, @ IBM Research, and Instructor @ Coursera

## License

Licensed under the Apache License. See [LICENSE](LICENSE)

## <h5 align="center"> © IBM Corporation 2023. All rights reserved. <h3/>
