# Ansible Role anisble-role-php

<span class="badges" align="center">
[![Build Status](https://travis-ci.org/hadenlabs/anisble-role-php.svg)](https://travis-ci.org/hadenlabs/anisble-role-php)
[![Stories in Ready](https://badge.waffle.io/hadenlabs/anisble-role-php.svg?label=ready&title=Ready)](http://waffle.io/hadenlabs/anisble-role-php)
[![GitHub issues](https://img.shields.io/github/issues/hadenlabs/anisble-role-php.svg)](https://github.com/hadenlabs/anisble-role-php/issues)
[![GitHub license](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square)](LICENSE)
</span>


This Ansible Role infuses antigravity, you are warned

Install it with the following command:

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
    php_version: 5.6
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
          php_version: 5.6
          php_modules:
            - php5-cli
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