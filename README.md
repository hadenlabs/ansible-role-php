# Ansible Role PHP

<span class="badges" align="center">
[![Build Status](https://travis-ci.org/dgnest/ansible-role-php.svg)](https://travis-ci.org/dgnest/ansible-role-php)
[![Stories in Ready](https://badge.waffle.io/dgnest/ansible-role-php.svg?label=ready&title=Ready)](http://waffle.io/dgnest/ansible-role-php)
[![GitHub issues](https://img.shields.io/github/issues/hadenlabs/ansible-role-php.svg)](https://github.com/hadenlabs/ansible-role-php/issues)
[![GitHub license](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square)](LICENSE)
</span>


Installs and configures [php][link-php] on a host.

## Requirements

 - Linux
   - none
 - OSX
   - [Homebrew][link-brew] must be installed.


## Role Variables

The default role variables in `defaults/main.yml` are:

    ---
    # defaults file for php


## Dependencies

none

## Example Playbook

See the [examples](./examples/) directory.

To run this playbook with default settings, create a basic playbook like this:

    - hosts: servers
      roles:
         - php

To install a specific version:

    - hosts: servers
      roles:
         - { role: hadenlabs.php }


## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Credits

- [Luis Mayta][link-author]
- [All Contributors][link-contributors]

[link-php]: https://php.net/
[link-brew]: http://brew.sh/

<!-- Other -->

[link-author]: https://github.com/luismayta
[link-contributors]: AUTHORS
