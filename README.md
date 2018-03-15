# helloworld-infrastructure-staging

This repo holds the Kubernetes configuration files for the helloworld application.

## Target Environment

Staging

## Usage

Changes pushed to the master branch should trigger the following actions:

 - a recursive application of the configuration files located under the kubernetes directory.

See the [cloudbuild.yaml](cloudbuild.yaml) file for more details.

