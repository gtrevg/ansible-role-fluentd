# Change Log

All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [2.0](https://github.com/gtrevg/ansible-role-fluentd/compare/v1.1...v2.0) - [2016-12-13]

These changes were made in order to bring the role more up to date with the latest ansible (2.x)

CHANGED:
* Updated tasks to use "{{ var_name }}" format for loops ( http://docs.ansible.com/ansible/playbooks_loops.html )
* Removed paths parameter from `include_vars` task
