# devops_end_to_end

## Goal: 
- A low to no cost End-to-End deployment of Microservices applications with the best DevOps Practices. Less ClickOps more Automation is the target.

## Initial thoughts:
- Lets create the infra where it goes into hibernate mode, when not in use, like entire infra should go offline until I start hitting the website.
- Secure the cloud account details, have one place configuration for all the secrets.

### Plan for Infrastructure: 
- Cloud: AWS or GCP
- Kubernetes: Combined on-prem and EC2 managed K8s deployment
- CICD: Github Actions
- Registry: Private AWS ECR if its free
- IAC: Terraform
- DNS: I have my own Domain I bought 1 year back, will use that
- GitOps: Because I love it- ArgoCD it is
- Autoscale: **Karpenter** because of Spot instances - no ASGs, no Launch templates, lets see how to make this possible
- Ingress: Nginx or istio

### Application:
- Google's Micro demo app: https://github.com/GoogleCloudPlatform/microservices-demo

### Notes:
- Never worked on coding. So zero knowledge with programming logic. Want to work on Coding part, may be go or python. Lets see how many working scripts I can write.
- Use helm charts to install apps or tools

Lets see how it goes.
