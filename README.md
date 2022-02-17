set_proxy4yum_dnf
=========

Configure the package manager to use some proxy.

Requirements
------------

None.

Role Variables
--------------

The input variables are defined in `defaults/main.yml`:

```yaml
set_proxy4yum_dnf_scheme: "http"
set_proxy4yum_dnf_hostname: "proxy.example.com" # FQDN or IP address
set_proxy4yum_dnf_port: "3128"
```

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
        - role: set_proxy4yum_dnf
          vars:
            set_proxy4yum_dnf_scheme: "http"
            set_proxy4yum_dnf_hostname: "proxy.example.com"
            set_proxy4yum_dnf_port: "3128"

License
-------

MIT

Author Information
------------------

Author: Joerg Kastning (Tronde)
