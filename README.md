Ansible playbooks for use with CentOS/Fedora Atomic hosts
=========================================================

A collection of Ansible roles and playbooks to automate tasks on CentOS and Fedora Atomic hosts.


Usage
-----

```
$ yum install -y ansible
$ ansible-galaxy install -r roles.txt
$ vi hosts
$ ansible-playbook -i hosts upgrade-atomic.yml
```


Used roles
----------

  * gbraad.atomic-upgrade  
    [Galaxy](https://galaxy.ansible.com/gbraad/atomic-upgrade/), [GitHub](https://github.com/gbraad/ansible-role-atomic-upgrade) / [GitLab](https://gitlab.com/gbraad/ansible-role-atomic-upgrade)


License
-------

Apache license 2.0


Authors
-------

| [!["Gerard Braad"](http://gravatar.com/avatar/e466994eea3c2a1672564e45aca844d0.png?s=60)](http://gbraad.nl "Gerard Braad <me@gbraad.nl>") |
|---|
| [@gbraad](https://twitter.com/gbraad)  |
