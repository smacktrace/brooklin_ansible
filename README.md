# brooklin_ansible
Linkedin Brooklin Ansible Install

## Set Ansible Remote User Var
```
export ANSIBLE_REMOTE_USER=<your remote user>
```

## Update hosts file
Update the hosts file and update the [brooklin] and [zookeeper] sections with the IP or FQDN of your respective servers

## Run Playbook
```
ansible-playbook -i hosts site.yml
```
