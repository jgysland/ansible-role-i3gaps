# Ansible Role: i3gaps

i3-gaps is a fork of i3wm, a tiling window manager for X11. This role will compile and install from source on Fedora and Debian based distros and install from official repo on Arch Linux.


## Requirements

None.

## Role Variables


Available variables:

    i3gaps_build_packages_state: present
    i3gaps_extra_packages_state: present
    i3gaps_packages_state: present

Directory where the i3-gaps git repository is cloned

    i3gaps_git_path: /tmp/i3gaps

Which branch/tag should be used

    i3gaps_version: gaps-next

Install some packages commonly used with i3-gaps (compton,dunst,rofi)

    install_i3gaps_extra_packages: true

## Dependencies

None.

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - bjornaru.i3gaps

## License

BSD

## Author Information

Role created in 2020 by Bjørnar Utseth.
