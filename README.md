Ansible role: WP-CLI
=========

Installs [WP-CLI](http://wp-cli.org/) which is a set of command-line tools for managing WordPress installations.

Requirements
------------

None.

Role variables
------------

|Key|Type|Description|Default|
|:--|:---|:----------|:------|
|wp_cli_phar_url|String|Download URL.|https://raw.github.com/wp-cli/builds/gh-pages/phar/wp-cli.phar|
|wp_cli_bin_path|String|Destination path.|/usr/bin/wp|

Dependencies
------------

None.

Example Playbook
------------

    - hosts: servers
      roles:
        - { role: shomatan.wp-cli }

License
-------

MIT

Author Information
------------------

Shoma Nishitateno