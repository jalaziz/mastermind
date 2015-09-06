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
