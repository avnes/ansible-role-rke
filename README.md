# ansible-role-rke

[![Publish to Ansible Galaxy](https://github.com/avnes/ansible-role-rke/actions/workflows/galaxy-publish.yaml/badge.svg)](https://github.com/avnes/ansible-role-rke/actions/workflows/galaxy-publish.yaml)

Ansible role for installing rke.

## Requirements

Poetry. Install it from <https://python-poetry.org/docs/>

## Role Variables

```yaml
rke_version: 3.7.2
```

## Dependencies

None

## Example Playbook

```yaml
- hosts: all
  roles:
     - { role: avnes.rke }
```

## For pip compability

```bash
poetry export --dev --output requirements.txt
```

## Test

```bash
poetry install
poetry shell
poetry run molecule test
```

## License

MIT

## Author Information

<https://github.com/avnes>
