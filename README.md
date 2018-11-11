# ericsysmin.kompose

This role installs kompose on linux systems.

## Requirements

None

## Role Variables

| Variable | Required | Default | Comments |
|----------|----------|---------|----------|
| `kompose_version` | No | `1.17.0` | Version of Kompose to be installed |

## Dependencies

None

## Example Playbook

```

- hosts: servers
  roles:
    - role: ericsysmin.kompose
      kompose_version: 1.17.0
```

## License

BSD

## Author Information

Eric Anderson
