# SonarQube for OpenShift

This repository contains a template for running a SonarQube 7.9 (LTS) with PostgreSQL persistence in OpenShift.

# Usage

    oc new-project sonarqube

    oc new-app -f sonarqube-template.yaml -n sonarqube

