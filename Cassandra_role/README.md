<p><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5e/Cassandra_logo.svg/1280px-Cassandra_logo.svg.png" alt="cassandra logo" title="cassandra" align="right" height="60" /></p>

Ansible Role: cassandra
=======================


This role installs Cassandra cluster and metrics exporter

Requirements
------------

Docker must be installed on host system. Due to test requirements those few lines have been commented out from meta/main.yml.

Example usage
-------------

Use it in a playbook as follows:
```yaml
- hosts: cassandra
  become: true
  roles:
    - SoInteractive.cassandra
```

Have a look at the [defaults/main.yml](defaults/main.yml) for role variables
that can be overridden.

TODO
----

- Replication factor in system_auth
