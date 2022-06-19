# devops-hiring

Hugo (Linux) installation steps: https://gohugo.io/getting-started/installing#debian-and-ubuntu

Command to generate static site (inside quickstart folder): `hugo`

Microk8s instructions: https://microk8s.io/

Nginx Ingress Controller instructions: https://kubernetes.github.io/ingress-nginx/deploy/#microk8s


## Instructions:

1. Clone the repo
2. Install all dependencies as per instructions and run the build command (`hugo server -D`) locally to test the website
3. Write an nginx configuration that will host the site
4. Write a dockerfile to dockerize the site hosting
5. Build docker image and push to dockerhub
6. Create new EC2 instance and run docker container (without k8s) there directly and demonstrate by accessing from public ip
7. Write k8s yaml file for deployment, service and ingress (assuming nginx ingress)
8. Create new EC2 instance and install microk8s on it.
9. Create another EC2 instance and it as a node of the microk8s cluster.
10. Install nginx ingress on k8s cluster (via helm-chart)
11. Apply k8s config to cluster
12. Scale up pods of nginx deployment
