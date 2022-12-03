redis
=================

Setup Redis server

OS Platform
-----------------

### Debian

- bullseye
- buster

Role Variables
--------------

### `redis_extra_cfg`

Redisの設定

### `redis_port`

Redisのポート

Example Playbook
--------------

```yaml
- hosts: servers
  roles:
    - role: redis
```

License
--------------

Apache License 2.0
