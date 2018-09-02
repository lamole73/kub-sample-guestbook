# kub-sample-guestbook
A Sample kubernetes configuration for kubernetes/guestbook:v2 image.

# Installation
Tag v1 or master contains a working kubernetes configuration, apply using:
kubectl create -f .

url of the application:
http://192.168.99.100:30100
where the ip should be:
- the ip of one of nodes of kubernetes cluster if running on a multinode cluster or
- the ip of minikube if running on minikube, i.e. find using 'minikube ip'