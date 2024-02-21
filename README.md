# Prometheus + Grafana + Ansible + Nginx

Pretty old roles, fixed some issues. Now you can start a secure monitoring stack with a push of a button. 

## Getting Started

1. **Update IP Addresses and Domains:**
- Update the IP addresses of your instances in the inventory file.
- Modify domains and upstreams for the Nginx reverse proxy.

2. **Update Service Versions:**
- In the `vars` section, update the versions of the services (Prometheus, Grafana, etc.) as needed.

3. **Run Ansible Command:**
- Execute the following Ansible command to set up Prometheus, Node Exporter, Alertmanager, Nginx, and Grafana services:

Ansible command: ansible-playbook -i inventory.yml playbook.yml