# Helm Charts Repository for Bare Metal Kubernetes - Local Development
- Designated repository to host under development Helm Charts for Bare Metal Kubernetes 

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
