# nexus-pro installation

### vagrant

    ansible-playbook nexus-pro.yml -e @"nexus-pro-vault.yml" --ask-vault-pass

### DC

    ansible-playbook -i <inventory> nexus-pro.yml -e @"nexus-pro-vault.yml" --become --become-user=iagcit -u <user> --ask-become-pass -k --ask-vault-pass


# nexus-oss installation

### vagrant

    ansible-playbook nexus-oss.yml --ask-vault-pass

### DC

    ansible-playbook -i <inventory> nexus-oss.yml -e @"nexus-pro-vault.yml" --become --become-user=iagcit -u <user> --ask-become-pass -k --ask-vault-pass



