# Ansible role: Google Chrome

[![Build Status](https://travis-ci.org/danbohea/ansible-role-google-chrome.svg?branch=master)](https://travis-ci.org/danbohea/ansible-role-google-chrome)

Installs & configures Google Chrome on macOS.


## Requirements

- macOS 10.11 or 10.12


## Role Variables

All role default variables are listed below along with their respective default values.

```yaml
google_chrome_AppleEnableSwipeNavigateWithScrolls: false
```

Toggles trackpad swipe navigation. Default is to disable it.


## Dependencies

- [danbohea.homebrew](https://galaxy.ansible.com/danbohea/homebrew)


## Example Playbook

```yaml
- hosts: macbook
  connection: local

  roles:
    - role: ansible-role-google-chrome
```

## License

MIT


## Author Information

This role was created by [Dan Bohea](http://bohea.co.uk) primarily for use with [Macsible](https://github.com/macsible/macsible).
