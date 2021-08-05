Installed eksctl from https://eksctl.io/introduction/

> eksctl create cluster --config-file=./eks-config.yaml
> eksctl create cluster --config-file=./eks-prod.yaml

Creating kubeconfig:
    - Above commands automatically create/update ~/.kube/config
    - Alternatively:  aws eks update-kubeconfig --region ap-southeast-2 --name DevTest --profile k8sspike


Installed k8s dashboard:  https://docs.aws.amazon.com/eks/latest/userguide/dashboard-tutorial.html

Added IAM users to system:masters role per https://docs.aws.amazon.com/eks/latest/userguide/add-user-role.html

Installed ArgoCD following https://argocd-autopilot.readthedocs.io/en/stable/Getting-Started/
    Public git repo:  https://github.com/Keidrych/gai-hackathon

