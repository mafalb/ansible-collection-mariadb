# Ansible Role mafalb.mariadb.server

## Basic Usage

```yaml
- name: install mafalb.mariadb.server
  hosts: localhost
  roles:
  - role: mafalb.mariadb.server
```

```yaml
- name: remove mafalb.epel.release
  hosts: localhost
  roles:
  - role: mafalb.epel.release
    state: absent
```

## Variables

### state

```yaml
state: present
```

```present``` is the default. you can remove epel-release with

```yaml
state: absent
```

---

## License

Copyright (c) 2021 Markus Falb <markus.falb@mafalb.at>

GPL-3.0-or-later
