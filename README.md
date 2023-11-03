# Primary objective for establishing Git Repo for Helm Charts
- Develop and demonstrate a proof of concept, showcasing the deployment and management of Kubernetes resources in a local Kubernetes cluster environment
- This environment will be deployed across three bare metal worker nodes, and the main focus will be on demonstrating the effective use of Helm Charts to streamline the process
- Main focus will be on demonstrating the effective use of Helm Charts to streamline the process.
- Utilize the ability to deploy these nodes using a persistent storage and establish a persistent volume claim

## The proof of concept project will encompass the following key components:

### Local Kubernetes Cluster Environment: 
- A local Kubernetes cluster will be set up, spanning across three bare metal worker nodes. This environment serves as the foundation for our project, enabling us to simulate a distributed Kubernetes cluster in a controlled, on-premises setting.

### Pod Deployment: 
- Within this local Kubernetes cluster, we will orchestrate the deployment of eight pods in a replica set. These pods will be strategically distributed across all three worker nodes, demonstrating the ability to efficiently manage containerized applications in a distributed environment.

### Persistent Storage: 
- The project will highlight the utilization of persistent storage for the deployed pods. 
- We will configure and showcase the creation of Persistent Volume Claims (PVCs), emphasizing the importance of data persistence for stateful applications.

#### *By executing this proof of concept, we aim to illustrate the seamless integration of Helm Charts with Kubernetes, empowering developers and operations teams to easily manage and deploy complex applications in Kubernetes clusters. Furthermore, it will emphasize the significance of persistent storage and its role in maintaining data integrity in containerized environments. This project will serve as a practical example of efficient Kubernetes resource management and Helm Chart usage, facilitating better understanding and adoption within the community.

## Helm Charts Repository for Bare Metal Kubernetes - Local Development
- Designated repository to host Dev Helm Charts for Local Bare Metal Kubernetes Deployment

## Helm Charts GitHub Repository
- [Helm Charts GitHub Repository](https://github.com/lagumen/helm-charts)

## Here are the Docker Images used  on the Helm Charts
- [Docker Images](https://github.com/lagumen?tab=packages)
- [nginx-www-ab Docker Image](https://github.com/users/lagumen/packages/container/package/nginx-www-ab)

## Regenerate index.yaml for git Helm Repo
```t
## Regenerate index.yaml
# Add new charts to existing repo
helm repo index --url https://lagumen.github.io/helm-charts/ --merge index.yaml .

```
