Install and configure wiki.js
=========

The role installs and configures wiki.js.

Role Variables
--------------

Example Playbook
----------------

```yaml
- hosts: all
  vars:
    wiki_js_db_pass: password

  roles:
    - role: tychobrouwer.wiki-js
      
    - role: tychobrouwer.wiki-js
      wiki_js_db_user: wikijs
      wiki_js_db_name: wikijs
      wiki_js_port: 3000
      wiki_js_user: wikijs
      wiki_js_group: wikijs
      wiki_js_db_port: 5432
```

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
