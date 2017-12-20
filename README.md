# Ansible Role MySQL

An Ansible role for installing MySQL.

## Role Variables

- `mysql_version` - MySQL version
- `mysql_python_version` - MySQLdb version

- `mysql__bind_address` - MySQL bind address (default 0.0.0.0)
- `mysql__port` - MySQL port (default 3306)

- `hostname` - MySQL hostname
- `mysql__localhost` - installed on localhost ?
- `mysql__root_password` - MySQL root pass
- `mysql__database` - MySQL test db
- `mysql__user` - MySQL user
- `mysql__password` - MySQL user

## Packages
| Package | Description | Status | Apt | Yum | Homebrew |
| ------- | ----------- | ------ | --- | --- | -------- |
| [MySQL]() | MySQL | Required | OK | NaN | NaN |
| [Workbench]() | MySQL Workbench | Recommended | OK | NaN | NaN |
| [phpmyadmin]() | PhpMyadmin | Recommended | OK | NaN | NaN |
