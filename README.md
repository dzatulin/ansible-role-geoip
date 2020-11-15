# Ansible Role GeoIP
Role for installing and updating GeoIP database
## Requirements
Ansible version: 2.9
Centos / Debian / Ubuntu
## Dependencies
None
## Example Playbook
```
- name: install MaxMind GeoIP
  hosts: "{{ var }}"
  vars:
    maxmind_update_userid: '111111'
    maxmind_update_licensekey: '0000000'
  roles:
     - role: ansible-role-geoip
```
