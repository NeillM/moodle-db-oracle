# moodle-db-oracle: Oracle XE for Moodle
[![Build Status](https://travis-ci.org/moodlehq/moodle-db-oracle.svg?branch=master)](https://travis-ci.org/moodlehq/moodle-db-oracle)

An Oracle XE instance configured for Moodle development based on [wnameless/docker-oracle-xe-11g](https://github.com/wnameless/docker-oracle-xe-11g)

# Example usage

```bash
docker run --name db0 -p 1521:1521 moodlehq/moodle-db-oracle
```

# Features:
* Oracle XE setup and preconfigured with user and moodlelib package installed (ready for Moodle install)
* Backed by [automated tests](https://travis-ci.org/moodlehq/moodle-db-oracle)

# See also
This container is part of a set of containers for Moodle development, see also:
* [docker-moodle](https://github.com/moodlehq/docker-moodle) a docker-composer based set of tools to get Moodle development running with zero configuration
* [moodle-php-apache](https://github.com/moodlehq/moodle-php-apache) PHP and Apache configured for Moodle development
* [moodle-db-mssql](https://github.com/moodlehq/moodle-db-mssql) Microsoft SQL Server for Linux configured for Moodle development
