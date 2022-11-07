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

# Searching official helm charts
On the artifact, hub search the required chart and select official.

![alt text](https://github.com/Yogita-Pol/imp-helm3-examples/blob/main/Images/artifactio_jenkins_official_image.jpeg)

# Installing charts from artifactory hub
- Please note although it highlights about artifactory hub similar steps can be used for other repos
- In an earlier section, we saw how to check to require repos.
- Once we select a specific chart it will give exact steps

![alt text](https://github.com/Yogita-Pol/imp-helm3-examples/blob/main/Images/helm_repo_add.jpeg)

It will add it to local repo.

![alt text](https://github.com/Yogita-Pol/imp-helm3-examples/blob/main/Images/helm_search_repo.jpeg)

Please note it still represents meta information and not actual,physical helm chart on your local machine.To install helm chart on your local machine we need to do helm pull. 

Helm pull will pull the actual chart to the local machine. –untar=true will untar it. 
![alt text](ttps://github.com/Yogita-Pol/imp-helm3-examples/blob/main/Images/helm_pull.jpeg)

# Other benefits of Helm Charts

- Sub chart- e.g., running backend (SQL, NoSQL database in the same chart). E.g., running MySQL in the same chart for application.
- Pre and post-deployment hooks for charts
- Chart package signing to verify integrity- beneficial for the production environment.
