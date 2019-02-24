# Ansible role for Apt-cache-ng server
Ansible role to setup and host a apt-cache-ng proxy server, for apt requestes.

## Requirements
There are no external dependencies.

## Role Variables
For now, pleae refer to the variables documented in [defaults/main.yml](../defaults/main.yml).

## Dependencies
There are no dependencies on other roles.

## Example Playbook
A trivial example:

    - hosts: apt-cache
      become: true
      roles:
       - apt-cache

## more Information
-   [Apt-Cacher NG homepage](https://www.unix-ag.uni-kl.de/~bloch/acng/)
-   [Debian: source](https://packages.debian.org/source/stretch/apt-cacher-ng)    , [github: clone](https://github.com/Efreak/apt-cacher-ng)
-   [die.net: apt-cache(8) linux man](https://linux.die.net/man/8/apt-cache)
-   [Debian: AptCacherNg](https://wiki.debian.org/AptCacherNg)
-   [Ubuntu: Apt-cache-server](https://help.ubuntu.com/community/Apt-Cacher-Server)
-   [tecmint: Setting up an ‘Apt-Cache’ Server Using ‘Apt-Cacher-NG’ in Ubuntu 14.04 Server](https://www.tecmint.com/apt-cache-server-in-ubuntu/)
-   [fabianlee.org: apt package cache using Apt-Cacher-NG](https://fabianlee.org/2018/02/11/ubuntu-a-centralized-apt-package-cache-using-apt-cacher-ng/)

## License
MIT

## Author Information
See <https://github.com/eideen>
