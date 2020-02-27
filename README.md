apt-repo
=========

_Ubuntu APT repo wrapper_

Primarily so we can use this in dependencies

Requirements
------------

Ansible 2.5 or above is highly recommended.

Role Variables
--------------

	apt_repo_filename:
    apt_repo_repo:
    apt_repo_state: present

Dependencies
------------

None

Example Playbook
----------------

    - hosts: localhost
      become: yes
      roles:
        - role: hyperized.apt-repo
          apt_repo_repo: deb http://archive.ubuntu.com/ubuntu bionic-updates main universe

License
-------

MIT

Author Information
------------------

Gerben Geijteman <gerben@hyperized.net>
