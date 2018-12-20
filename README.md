# nso_vnf_cisco_csr1k_asav

Ansible playbook to launch Cisco CSR1K and Cisco ASAv in Openstack via NSO/ESC.  

### Playbooks

-cisco-csr1k-asav-deploy.yaml

Creates a CSR1k and ASAv with day0 configuration

-cisco-csr1k-asav-undeploy,.yaml

Remove a CSR1k and ASAv

### Requirements

- Openstack VIM
- NSO 4.2.7
- tailf-nfvo
- tailf-nfvo-esc
- ESC NED
- ESC 4.3
- Ansible 2.6.0

### Contacts:

- Jason Mah (jamah@cisco.com)
- Santigo Flores (sfloresk@cisco.com)