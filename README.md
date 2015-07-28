Celery
=========
celery installer

Requirements
------------

Role Variables
--------------
        celery_home: /var/lib/celery
        celery_version: 3.1.18
        celery_log_path: /var/log/celery.log
        celery_bin: /usr/local/bin/celery
        celery_pip_bundles: [redis]
        celery_rotate_logs: true
        celery_logrotate_rotation_interval: daily
        celery_logrotate_max_archives: 7

Example Playbook
----------------

        ---
        - hosts: all
          sudo: yes
          roles:
            - nowait-tools.celery


License
-------

MIT

Author Information
------------------

Produced by NoWait
