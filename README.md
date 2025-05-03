# Ansible AWS

This was not finished due to me having issues with provisioning the Windows EC2 instances (specifically, configuring a WinRM listener securely and getting the credentials of the machine for Ansible to then use for further configuration), although this repository also highlights why IaC should have been utilised.

Furthermore, the goal of "create_windows_domain" is a bit dated (creating an "on-prem" Exchange server which would have taken a while for the install, and cloud-native VDI like Amazon WorkSpaces or Azure Virtual Desktop should have been preferred over building an RDS Farm in AWS).

Have made public as some of the playbooks may be useful in the future.
