correcthorse.nodejs
=========

A role for installing nodejs.

Variables
---------

| Variable			| Default			| Notes				|
| :---				| :---				| :---				|
| nodejs_install_bower		| false				| global install		|
| nodejs_bower_version		| '>0'				| 	 			|
| nodejs_install_gulp		| false				| global install		|
| nodejs_gulp_version		| '>0'				| 	 			|
| nodejs_install_grunt-cli	| false				| global install		|
| nodejs_grunt-cli_version	| '>0'				| 	 			|

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
