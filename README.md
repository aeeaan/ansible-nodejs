correcthorse.nodejs
=========

A role for installing nodejs.

IMPORTANT: This role will fail on a system that already has nodejs packages installed, ie the EPEL packages. Installed packages are from upstream repository and the nodejs package comes with npm.

Variables
---------

| Variable			| Default			| Notes				|
| :---				| :---				| :---				|
| nodejs_version          | 6           | only accepts major versions that upstream has repos for, ie 6, 7, 8 |
| nodejs_install_bower		| false				| global install		|
| nodejs_bower_version		| '>0'				| 	 			|
| nodejs_install_gulp		| false				| global install		|
| nodejs_gulp_version		| '>0'				| 	 			|

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: correcthorse.nodejs }

License
-------

MIT

Author Information
------------------

* [Joshua Rusch](https://correct.horse/)
