# onlybooks-server
nginx server for onlybooks capstone project

Deploy kubernetes deployment and services
    kubectl apply -f .
Run a port forward to expose a port on your local
    kubectl port-forward service/library-webserver-service 8080:80
