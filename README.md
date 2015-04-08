<img src="http://www.elao.com/images/corpo/logo_red_small.png"/>

# Ansible Role: <skeleton>

This role will assume the setup of <skeleton>

It's part of the ELAO [Ansible stack](http://ansible.elao.com) but can be used as a stand alone component.

## Requirements

- Ansible 1.7.2+

## Dependencies

None.

## Installation

Using ansible galaxy:

```bash
ansible-galaxy install elao.<skeleton>
```
You can add this role as a dependency for other roles by adding the role to the meta/main.yml file of your own role:

```yaml
dependencies:
  - { role: elao.<skeleton> }
```

## Role Handlers

|Name|Type|Description|
|----|----|-----------|
<skeleton>

## Role Variables

### Configuration templates

|Name|Default|Type|Description|
|----|-------|----|-----------|
<skeleton>


### Configuration definitions

|Name|Default|Type|Description|
|----|----|-----------|-------|
<skeleton>

### Configuration example

<skeleton>

## Example playbook

    - hosts: servers
      roles:
         - { role: elao.<skeleton> }

# Licence

MIT

# Author information

ELAO [**(http://www.elao.com/)**](http://www.elao.com)

# Guidelines

---

elao_motd_type:     elao
elao_motd_template: ~
elao_motd_message:  "California - 1993"

