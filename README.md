# Ansible Role: osm2pgsql

[![Build Status](https://travis-ci.org/cecepm/ansible-role-osm2pgsql.svg?branch=master)](https://travis-ci.org/cecepm/ansible-role-osm2pgsql)

Install osm2pgsql from sources.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    osm2pgsql_bin: /usr/local/bin/osm2pgsql
    osm2pgsql_src_dir: /opt/src/osm2pgsql

## Dependencies

None. Tested on Ubuntu 14.04.

## Example Playbook

Using default value

    - hosts: server
      roles:
      - cecepm.osm2pgsql

## License

MIT / BSD

## Author Information

This role was created in 2014 by [Cecep Mahbub](http://ngadimin.org/).
