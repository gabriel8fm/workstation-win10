Description:
------------
This role it's used to install and prepare my local Windows 10 environment.

Requirements:
------------
- Ansible only works on linux, so the environment needs to have an active wsl.
- In the installation [folder](https://github.com/gabriel8fm/ansible-windows10/tree/master/setup) are the powershell scripts needed to activate winrm. Remembering to run them in administrator mode.

How to use:
-----------
ansible-playbook -i hosts playbook.yml -u <Admin> -k 

[Ansible Windows documentation](https://docs.ansible.com/ansible/latest/user_guide/windows_setup.html)
