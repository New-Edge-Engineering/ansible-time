# Ansible Time Role #

Ansible role to make sure network time protocol is installed and running.
Feedback, bug-reports, requests, is welcomed and can be done via
[github issues](https://github.com/ansibles/timezone/issues).

## Requisites ##
The following software is needed to use this project:

* Python 2.x
* [virtualenv](http://pypi.python.org/pypi/virtualenv) & [virtualenvwrapper](http://www.doughellmann.com/projects/virtualenvwrapper/)

## Installation ##
The following assumes all commands will be executed with a new cli session:

    mkvirtualenv ansible
    easy_install ansible
    cd $ROLES_PATH
    ansible-galaxy install neel.time --roles-path .

## Requirements & Dependencies ##
- Tested on Mac OS X with Ansible 1.5.

## License ##

Licensed under the MIT License. See the LICENSE file for details.
