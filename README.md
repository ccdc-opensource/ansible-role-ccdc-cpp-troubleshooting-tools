# Ansible Role: Install troubleshooting tools

Install a set of useful troubleshooting tools for C++ software.

This is to support build checkers and developers in identifying problems on builds.

### Linux

- strace
- htop
- valgrind

### macOS

- m-cli
- clang-format
- Midnight Commander
- sqldiff
- sqlite
- ctags
- screen

### Windows

- Midnight Commander

## Requirements

None.

## Role Variables

None.

## Dependencies

None.

## Example Playbook

    - hosts: all
      roles:
        - ccdc-cpp-troubleshooting-tools

## License

MIT / BSD

## Author Information

This role was created in 2020 by Claudio Bantaloukas, based on existing roles at CCDC, by Jeff Geerling and google searches