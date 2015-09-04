Bash
========

Install zsh and oh-my-zsh
Backup existing zsh config files
Copy latest zsh config files

Requirements
------------

python-pycurl and python-software-properties installed.

Example Playbook
-------------------------

    - hosts: servers
      vars:
         user: alex
      roles:
         - devbox.oh-my-zsh

License
-------

LGPL

Author Information
------------------

Alex Lourie, djay.il@gmail.com
Sean Azlin, sazlin@gmail.com

Based on bash work by:
------------------

Jasper N. Brouwer, jasper@nerdsweide.nl

Ramon de la Fuente, ramon@delafuente.nl
