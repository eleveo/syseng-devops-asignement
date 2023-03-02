# Automation

Nobody wants to do application deployment manually. Therefore provide an **Ansible playbook** which will deploy your application with following milestones and requirements

- Application is idempotent
- Ansible deploys a Kubernetes cluster distribution (preferably something light)
- Your microservice from Level 2 is deployed on a cluster (If you've skipped Level 2 Use [microbot](https://hub.docker.com/r/dontrebootme/microbot/) instead)
- Ansible [best practices ](https://docs.ansible.com/ansible/2.8/user_guide/playbooks_best_practices.html#best-practices) are followed
- We should be able to start everything with a simple `ansible-playbook ... ` command
- Application is running after system reboot

## OPTIONAL:
- Kubernetes Cluster is multinode

# Operation
< your brief documentation on how to use the application >

# Known Issues
< fill in your implementation limitations >