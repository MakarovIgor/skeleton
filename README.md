# php skeleton

Skeleton for creating small php packages with static analyzing and unit testing

![GitHub CI](https://github.com/otis22/php-skeleton/workflows/CI/badge.svg)
![Travis CI](https://api.travis-ci.org/otis22/php-skeleton.svg?branch=master)
[![Coverage Status](https://coveralls.io/repos/github/otis22/php-skeleton/badge.svg?branch=master)](https://coveralls.io/github/otis22/php-skeleton?branch=master)

## Local work

For run all tests
```shell
make all
```
or connect to terminal
```shell
make exec
```
*Dafault php version is 7.4*. Use PHP_VERSION= for using custom version. 
```shell
make all PHP_VERSION=8.0
# run both 
make all PHP_VERSION=7.4 && make all PHP_VERSION=8.0
```

all commands
```shell
# security check
make security
# composer install
make install
# composer install with --no-dev
make install-no-dev
# check code style
make style
# run static analyze tools
make static-analyze
# run unit tests
make unit
#  check coverage
make coverage
```

## Adopt for you 

- Click on [Use template button](https://prnt.sc/w7avaw) 
- Put your code to src/ tests/ directory
- Delete config files for unused CI systems
- Change project data in composer.json, README and Makefile


## Comments 

- Repo with analyze tools: https://github.com/exakat/php-static-analysis-tools
- Repo for gitlab-ci php https://gitlab.com/gitlab-org/gitlab-foss/-/blob/master/lib/gitlab/ci/templates/PHP.gitlab-ci.yml
