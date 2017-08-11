# Ansible Role PHP

[![Build Status](https://travis-ci.org/labpositiva/ansible-role-php.svg)](https://travis-ci.org/labpositiva/ansible-role-php)
[![GitHub issues](https://img.shields.io/github/issues/labpositiva/ansible-role-php.svg)](https://github.com/labpositiva/ansible-role-php/issues)
[![GitHub license](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square)](LICENSE)


```bash
$ ansible-galaxy install labpositiva.php

```

Requirements
------------

 - Linux
   - none
 - OSX
   - none



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

None


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

Made with :heart: ️:coffee:️ and :pizza: by [labpositiva][link-company].

- [All Contributors][link-contributors]


---

[link-author]: https://github.com/luismayta
[link-contributors]: contributors
