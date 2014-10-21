toolkit
=======

A smattering of tools I wrote to help me do stuff

Cisco-ssh.py
------
A script for ssh'ing into a cisco device and running commands, if you (or the org you work for) doesn't have a prebuilt automated way of doing this.

Get-Portstate
----
A tool that I found on powershelladmin.com - the intention here is to just host it on github so that it can be easily accessed, and used by way of the 'powershell IEX' method seen in other haxy projects.
You can call it over the internet from powershell by issuing this command:
IEX (New-Object Net.WebClient).DownloadString('http://is.gd/cQW9sE'); Get-PortState

At that point 'Get-PortState' should be available for you to conduct portscans.
