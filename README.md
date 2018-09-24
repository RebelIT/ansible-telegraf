# ansible-telegraf
ansible for installing telegraf

### Usage:
* Update hosts with IP or Hostname in hosts file

  ```
  --ask-sudo-pass may be required if running reboot role due to your local setup
  ansible-playbook telegraf_setup.yml -i hosts --ask-sudo-pass
  ```

### Secrets:
* Upload your ssh key to your pi else ansible will fail

  ```
  wifi_ssid: 'xxx' #wifi ssid
  wifi_psk: 'xxx' #wifi password
  dak_token: 'xxx' #your personal DAK url
  ```
