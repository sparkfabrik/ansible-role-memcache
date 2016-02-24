Role Name
=========

Ansible Galaxy role for insalling memcache

Role Variables
--------------

`
memcache_memory: '128'
memcache_port: '12111'
memcache_ip: '127.0.0.1'
`

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: sparkfabrik.memcache, memcache_memory: '256', memcache_port: '12111', memcache_ip: '127.0.0.1' }

License
-------

BSD
