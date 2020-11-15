# Ansible Role: Windows Subsystem for Linux (WSL)

An Ansible role that configures a distro within the [Windows Subsystem for Linux (WSL)](https://docs.microsoft.com/en-us/windows/wsl/). This role does not handle installation of WSL or a distro - it only manages WSL-specific configuration items within the distro that is running.

## Status

This role is in its alpha stages. This role should not be considered production-ready; use at your own risk.

## Requirements

Target hosts will need Windows Subsystem for Linux supported and enabled. This role does not handle the installation of WSL. There is no distro-specific content in the role, but the role has only been tested using Ubuntu 18.04 LTS.

## Role Variables

TODO need to describe variables once they have been defined - see the default explanation below

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

## Dependencies

None.

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

See also the example playbook for [using Windows as an Ansible control node](TODO add the link to a specific portion of the document).

## Development

Testing - TODO add a link to documentation

## License

MIT

## Author Information

This role was created in 2020 by James Tarka. Contributions are welcome - see [Contributing](CONTRIBUTING.md).
