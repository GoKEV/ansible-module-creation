[![GoKEV](http://GoKEV.com/GoKEV200.png)](http://GoKEV.com/)

<div style="position: absolute; top: 40px; left: 200px;">

# motd-splash

This role plays with some various non-traditional Ansible modules.  Ultimately, I want a simple example in Perl, BASH, and maybe even *gasp* PHP.



## Here's an example of how you could launch this role:
<pre>
ansible-playbook -i inventory.hosts module-bash.yml 

or
 
ansible-playbook -i inventory.hosts module-perl.yml
</pre>

## Example Playbook called module-bash.yml:

<pre>
---
- name: Simple Playbook
  hosts: local
  gather_facts: no
  connection: local

  roles:
  - module-bash

</pre>


Author Information
------------------

Kevin Holmes :: kev@GoKEV.com

Bash module was sourced from https://github.com/pmarkham because he's a genius and had already built something that I wanted!  I'm including the module (currently unmodified) in this repo so that it's a complete example.
Please refer to his thorough documentation on the full use of this BASH module: 



This project was created in 2018 by [Kevin Holmes](http://GoKEV.com/).

