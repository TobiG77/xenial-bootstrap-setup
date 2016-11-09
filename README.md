Role Name
=========

Personal collection of tasks to get my workstation ASAP into a productive state.

Requirements
------------

For from scratch installations.

python2.7 for ansible 
aptitude for ansible
ansible itself

Role Variables
--------------

None.

Dependencies
------------

None.

Example Execution
-----------------

```
sudo apt install python2.7 aptitude ansible
sudo mkdir /etc/ansible/roles

curl https://raw.githubusercontent.com/TobiG77/xenial-bootstrap-setup/master/test-playbook.yml > xenial-bootstrap.yml
sudo ansible-galaxy install TobiG77.xenial-bootstrap-setup
sudo ansible-playbook xenial-bootstrap.yml
```
 
Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

or in your own playbook:

    - hosts: localhost
      roles:
         - { role: tobig77.xenial-bootstrap-setup }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
