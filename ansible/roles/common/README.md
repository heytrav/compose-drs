# Ansible - Common Tasks

Things I finding myself doing over and over again in playbooks

# Usage

You can use this role by adding it to your project as a git submodule, then
include the tasks directly.

You also need to set `common_osfamily` to one of either `redhat` or `debian`.
Simplest way is to add this to `group_vars/all/main.yml`
