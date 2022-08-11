Lighthouse-role
=========

Устанвливает Vector на систему Centos 7

Requirements
------------

Роль работает только на ОС CentOS 7.

Role Variables
--------------

| Переменная  | Назначение  |
|:---|:---|
| lighthouse_dest | Указывает путь куда поместить конефигурационный файл для веб сервера |
| lighthouse_url | указывает адрес до репозетория https://github.com/VKCOM/lighthouse.git |

Example Playbook
----------------

```yml
- name: Install lighthouse
  hosts: lighthouse
  remote_user: centos
  roles:
    - lighthouse-role
```

License
-------

MIT

Author Information
------------------

Розум Сергей
