# Ansible Role: Varnish 

Forked role from Geerlingguy Ansible Role Varnish (https://github.com/geerlingguy/ansible-role-varnish). 

This role installs Varnish 5.1, 5.0, 4.1 or 4.0 from packagecloud.io instead of the upstream version. It also deploys a VCL optimized for WordPress and daily cronjob warmer script written in Bash.  

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)


# Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yml
- hosts: servers
  roles:
    - ansible-varnish-wordpress
```

## License

MIT / BSD

