# win-tso-playbook


[windows]<br>
win2012r2<br>

[windows:vars]<br>
ansible_user=user1@TEST007.ORG<br>
ansible_password={{ hide_password}}<br>
ansible_connection=winrm<br>
ansible_winrm_transport=kerberos<br>
ansible_port=5985<br>
