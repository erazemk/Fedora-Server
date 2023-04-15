# Fedora Server Setup

This repository holds an Ansible playbook for setting up a Fedora Server on a
Raspberry Pi 3, which was done as part of a university course.

The code in this repository contains a hash of a Linux user's password.
This is intentional, as the code will not be used in a production scenario
and the server will only be accessible on a local network and logins are only
possible with an SSH key, not using the password.
In a production environment, Ansible Vault or a similar solution should be used
instead.

## License

The code in this repository is licensed under the [MIT license](LICENSE).
