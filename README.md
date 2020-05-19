# gitops-myproject-k8s

This repo is for "myproject" and no its not the project in ArgoCD context. A project would be a logical separation on business/company level for instance a new customer, service or product.

The "myproject" project is comprised of the `charts/helm-myapp` chart, which deploys the https://github.com/musabmasood/gitops-myapp service. That repository also autocommits on this one when there is a new tag released.
