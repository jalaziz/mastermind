mastermind
==========

## Instructions

1. Modify the example site.yml and vars/secret.yml according to your needs

  ```sh
  cd playbooks
  mv site.yml.example site.yml
  mv vars/secret.yml.example vars/secret.yml
  ```

2. Install ansible

  ```sh
  pip install ansible
  ```

3. Run the playbooks
  ```sh
  ansible-playbook -i change.me, site.yml
  ```

## TO DO

* Upgrade ruTorrent to 3.7 (changed packaging)
* ~~Upgrade rTorrent to 0.9.6 (need to update the PPA)~~ - 0.9.6 is available on my [PPA](https://launchpad.net/~jalaziz/+archive/ubuntu/rtorrent)
* Add configuration instructions to README
