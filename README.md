# ansible-telegraf
ansible for installing telegraf

### Usage:
* Update hosts with IP or Hostname in hosts file

  ```
  --ask-sudo-pass may be required if running reboot role due to your local setup
  ansible-playbook telegraf_setup.yml -i hosts
  ```
