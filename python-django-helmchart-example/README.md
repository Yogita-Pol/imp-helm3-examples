# This document explain steps to install custom helm chart in kubernetes cluster

1.Created dockerfile for custom django application (django-python based framework,for dockerfile took reference from  https://github.com/shreys7/django-todo.git)

2.Created docker image and tested application on local machine.

3.Push docker image to docker hub repository.

4.Created helm chart in minikube with reference of this docker image.

5.Deployed django application in  minikube 
