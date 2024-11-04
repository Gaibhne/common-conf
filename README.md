# Common Configurations

This repository just holds some settings, configurations, package sets and so on that I personally
find useful and like to have on every system that I regularly use via CLI. YMMV very much.

Run against localhost via: `ansible-playbook --connection=local --inventory 127.0.0.1, all.yml`

## Bash

* Install and configure https://github.com/magicmonty/bash-git-prompt

## Git

* Install and configure https://github.com/magicmonty/bash-git-prompt (see [Bash](#bash))
* Configure various user level aliases that I found useful. For a list see `roles/git/tasks/main.yml`
