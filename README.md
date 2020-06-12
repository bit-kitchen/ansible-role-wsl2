ansible-role-wsl2
=================

Install WSL 2 on Windows 10. <https://docs.microsoft.com/en-us/windows/wsl/install-win10>

Note: WSL 2 requires Windows 10, updated to version 2004, Build 19041 or higher. This role will error out if on Windows but version requirement not met.

This role will do nothing on Linux, so that it can be depended on by roles compatible with both Linux and Windows.

    ansible-galaxy install bit_kitchen.wsl2

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: win_servers
      roles:
        - bit_kitchen.wsl2

License
-------

[MIT](LICENSE)

Author Information
------------------

[bit.kitchen](https://github.com/bit-kitchen)
