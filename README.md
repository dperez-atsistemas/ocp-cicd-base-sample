openshift-cicd-base-sample
====================

A sample app with a jenkins pipeline to be deployed on openshift environments

- Prerequisites:

    - An openshift cluster installed and configured.
    - Credentials to access the cluster
    - oc client and git installed
  

- Deploy instructions:

    - Clone or download this repository and open the folder in terminal.
    - Login to the cluster: oc login -u <user> <hostname>
    - Run ./resources/deploy.sh (Execution time: around 5 minutes)
    

- Clean environment

    - Run ./resources/deploy.sh --delete