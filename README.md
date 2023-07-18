# NP_ansibleautomation
CI/CD pipeline for network automation using Ansible

# Network Tasks on Roles directory
a) Interface configurations (IPv4 and IPV6)
b) OSPFV2 and OSPFV3 Routing (IPV4 and IPV6)
c) BGP Routing (IPV4 and IPV6)
d) EIGRP Routing

# Jenkins compatibility
The ansible code can be executed in Jenkins build job. The playbook  `all.yaml` executes all network automation tasks.

# Running a code
On terminal type
`ansible --playbook all.yaml --ask-vault-passs` 

