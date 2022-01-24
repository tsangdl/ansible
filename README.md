**My Playbooks**
Once a vm is built...
The vm should have userids: 
dt / N0{2},{3}
root / N0{2},{3}

To get ansible working
Get dt rsa key into authorized_keys file on the vm

visudo
Change:
# Allow members of group sudo to execute any command
#%sudo  ALL=(ALL:ALL) ALL
To:
# Allow members of group sudo to execute any command
#%sudo  ALL=(ALL:ALL) ALL
%sudo   ALL=(ALL:ALL) NOPASSWD: ALL

