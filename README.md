Playbook to use on clean Fedora for install minimal Devops Tools.

First step: Install Ansible

```
sudo dnf install ansible
```

Second step: Execute the command.

```
sudo ansible-playbook -i hosts playbook.yml
```