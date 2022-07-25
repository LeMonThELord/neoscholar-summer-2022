# Assignment 3

## Description

This folder contains files for assignment 3

## Hierarchy

- Part I

    This folder contains all the files required to create the sample-time-app, the two most important files are: 

    1. run.py

        This python script contains the logic of running the website, including hello world page and the time page.

    2. Dockerfile

        This is a plain-text docker image config file, modified to build the image with minimal disk size and modification to the base image.

- Part II

    This folder contains all the files required to accomplish part II of the assignment, the files included are: 

    1. *2048-docker*

        This folder includes the 2048 code from https://github.com/bingosummer/2048 release v2.0, and a Dockerfile basing on nginx:1.15-alpine

    2. ns2022.pem

        This is the key for AWS key pair.

    3. management-cluster.yaml and workload-cluster.yaml

        These are configs for tanzu to create clusters.