# Orchestrated Dev Environment with Kubernetes
 A simple dev environment for Python with Kubernetes and Docker.

 ## Build Process
 1. Build the Docker image within the `app` directory with `docker build -f Dockerfile -t hello-world:latest`
 2. You may initialize the container to verify, if needed.
 3. `docker image ls` should verify if image was added to the list.
 4. Run the following command in the root of the repostiory `kubectl apply -f deployment.yaml` to deploy a load-balanced service using the pods.
 5. To verify the pods are running use `kubectl get pods`

 ## Reference
 Followed [this blog post](https://kubernetes.io/blog/2019/07/23/get-started-with-kubernetes-using-python/) to create this repository. 

