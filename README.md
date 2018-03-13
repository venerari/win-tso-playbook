# win-tso-playbook


[windows]
win2012r2

[windows:vars]
ansible_user=user1@TEST007.ORG
ansible_password={{ hide_password}}
ansible_connection=winrm
ansible_winrm_transport=kerberos
ansible_port=5985