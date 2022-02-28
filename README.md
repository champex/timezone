Role Name
=========

timezone

Variables
---------

```
timezone: Europe/Paris

```

Usage
-----

playbook.yml
```
- hosts: localhost
  vars:
    timezone: Japan/Tokyo
  roles:
    - timezone

```

requirements.yml
```
- src: github.com:champex/timezone.git
  scm: git
  name: timezone
```

License
-------

`UNLICENSE<http://unlicense.org>`
This is free and unencumbered software released into the public domain.