# Kubernetes with Docker Desktop

Prerequisites:
1. Install [Docker Desktop](https://www.docker.com/products/docker-desktop/)
2. Install [kubectl](https://kubernetes.io/docs/reference/kubectl/kubectl/)
3. Enable Kubernetes in Docker Desktop

Steps:
1. Set `kubectl` context to `docker-desktop`
2. Apply all the addons to the cluster
3. Apply configs for local development
4. Run `npm run docker:admin-user-token` to get the admin user token
5. Update the applications configuration
6. Apply the applications
7. Visit the [kubernetes dashboard](http://localhost:8001/api/v1/namespaces/kube-system/services/https:kubernetes-dashboard:/proxy/) to check the cluster status
8. Update `/etc/hosts` to point to the domain set in the applications
