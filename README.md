# gitops
DevOps focuses on automating the process of software development from start to finish. This includes tasks like code testing, deployments, and monitoring. GitOps, on the other hand, takes a more declarative approach, focusing on treating infrastructure as code. This allows for flexibility and speed when making changes to your infrastructure.

# Changes require -
    1. /base/apps/be/deploy.yaml => image
    2. /base/apps/fe/deploy.yaml => image
    3. deployments/node-app/kustomization.yaml => image
    4. deployments/node-app/app.yaml => repoURL, targetRevision, namespace