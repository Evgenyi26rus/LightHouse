LightHouse
=========

This role install lighthouse 

Requirements
------------

1. ОС Centos versions: 7/8
2. Предустановленное ПО с БД Clickhouse
3. Установленное ПО git
4. Установленное ПО nginx

Role Variables
--------------

Место и условия для получения ПО описано в файле: [main.yml](vars%2Fmain.yml)

Dependencies
------------

ПО nginx

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: lighthouse }

License
-------

MIT

Author Information
------------------

Evgenyi Korshunov