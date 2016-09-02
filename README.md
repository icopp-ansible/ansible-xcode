# ansible-xcode

Install Xcode via the Mac App Store. Does nothing on non-macOS platforms.

## Dependencies

* [icopp.mas-cli](https://github.com/icopp/ansible-mas-cli) (included as repository dependency)

## Example Playbook

```
  - hosts: all
    roles:
      - role: icopp.xcode
```

## License

MIT
