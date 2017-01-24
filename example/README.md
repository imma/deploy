# Example deploy

    deploy -vvvv -i .ansible.hosts -e ansible_ssh_port=2222 -e scp_if_ssh=True -l all local.yml
