# Imp-helm3-examples
This git repo give general guideline to setup some common helm charts
important helm charts
- jenkins
- sonarqube
- custom helm chart for python application

## Helm chart Introduction

Although a helm chart is a chart, it is nothing to do with graphical representation or dashboards.

## Need for Helm chart

- Complexity management
  - One can build charts for complex applications with lot of k8s objects 
  - Provide repeatable installation
- Easy updates
- Simple sharing 
  - Can be versioned 
  - Can be host on git repo as well
- Rollbacks
  - Possible to rollback to earlier old versions

## Important notes
- Helm is a package manager for k8s
- The Helm package is known as a chart.
- Helm chart help define, install and upgrade k8s complex applications
- These charts can be versioned, shared, and published.
- Already, a huge amount of charts are available with Helm. at the time of writing this content, nearly 11000 charts are available https://artifacthub.io/

# Installation of Helm chart
- Based on your OS.exact steps for installing the helm chart is available at this URL

- When we run the helm version, it will provide the helm version. It will also ensure that the helm is installed properly.
  
![alt text](https://github.com/Yogita-Pol/imp-helm3-examples/blob/main/Images/helm_version.jpeg)




![alt text](ttps://github.com/Yogita-Pol/imp-helm3-examples/blob/main/Images/helm_pull.jpeg)

