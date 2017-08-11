# Ansible Role PHP

[![GitHub tag](https://img.shields.io/github/tag/labpositiva/ansible-role-php.svg?maxAge=2592000)](https://github.com/labpositiva/ansible-role-php)
[![Build Status](https://travis-ci.org/labpositiva/anisble-role-php.svg)](https://travis-ci.org/labpositiva/anisble-role-php)
[![GitHub license](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square)](LICENSE)


```bash
$ ansible-galaxy install labpositiva.php

```
Requirements
------------

None



## Role Variables

Here is the list of all variables and their default values:

```yaml
    ---
    # defaults file for labpositiva.php
    php_version: 7.0
    php_modules: []
    php_pecl_extensions: []
```

## Dependencies

none

## Example Playbook

See the [examples](./examples/) directory.

To run this playbook with default settings, create a basic playbook like this:

```yaml
    - hosts: servers
      roles:
        - labpositiva.php
          php_version: 7.0
          php_modules:
            - php7.0-cli
          php_pecl_extensions:
          - xdebug
          - zendopcache
```

## License

MIT

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Credits

- [author][link-author]
- [All Contributors][link-contributors]


---
Copyright © 2017, labpositiva

[link-author]: https://github.com/luismayta
[link-contributors]: contributors