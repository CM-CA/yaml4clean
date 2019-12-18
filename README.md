Playbook to use on clean Fedora for install minimal Devops Tools.

First step: Install Ansible

```
sudo dnf install ansible
```

Second step: Wifi Adapter Install.

```
sudo ansible-playbook -i hosts WifiAdapter_Install.yml \ --extra-vars 'ansible_become_pass=YOUR-PASSWORD-HERE'
```

Third step: Devops Tools Install.

```
sudo ansible-playbook -i hosts Clean_Install.yml \ --extra-vars 'ansible_become_pass=YOUR-PASSWORD-HERE'
```