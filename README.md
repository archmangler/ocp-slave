Docker image for jenkins dynamic agents running on OCP (Kubernetes)
===================================================================

- Custom additions for infrastructure as code deployments using terraform to Azure Cloud
- Derived from the OCP slave agent CentOS Docker image
- meant to work with the Jenkins kubernetes plugin and Docker plugins to spawn on-demand slaves.
- ensure terraform binary is present in working dir before doing "docker build ."

Includes:

 - terraform
 - ansible
 - tower-cli
 - pip
 - virtualenv
 - az cli
 - jq
