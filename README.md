# Ansible Role PHP

<span class="badges" align="center">
[![GitHub tag](https://img.shields.io/github/tag/hadenlabs/ansible-role-php.svg?maxAge=2592000)](https://github.com/hadenlabs/ansible-role-php)
[![Build Status](https://travis-ci.org/hadenlabs/anisble-role-php.svg)](https://travis-ci.org/hadenlabs/anisble-role-php)
[![GitHub license](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square)](LICENSE)
</span>


```bash
$ ansible-galaxy install hadenlabs.php

```
Requirements
------------

None



## Role Variables

Here is the list of all variables and their default values:

```yaml
    ---
    # defaults file for hadenlabs.php
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
        - hadenlabs.php
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
Copyright © 2016, hadenlabs

<!-- Other -->

[link-author]: https://github.com/luismayta
[link-contributors]: contributors