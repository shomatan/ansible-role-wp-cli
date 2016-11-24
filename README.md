# Ansible role: wp-cli
Installs wordpress command line interface.

## Requirements
None.

### Role variables
|Key|Type|Description|Default|
|:--|:---|:----------|:------|
|wordpress_wp_cli_phar_url|String|Download URL.|https://raw.github.com/wp-cli/builds/gh-pages/phar/wp-cli.phar|
|wordpress_wp_cli_bin_path|String|Destination path.|/usr/bin/wp|

### Dependencies
None.

### Example Playbook

```yaml
- hosts: all
  roles:
    - { role: wp-cli }
  vars:

```
