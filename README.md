# Cybersecurity game "Secret laboratory"

Linear game for KYPO with APG and a sandbox created by Cyber Sandbox Creator.

This game uses `kali` and `debian-10` images from MUNI-KYPO-IMAGES, which need to be available in OpenStack for use with KYPO CRP. To get and upload the images.

## Game Levels Summary
- host scan with `nmap`
- exploit `webmin` with `metasploit`
- host exploration and analysis of `.bash_history`
- private SSH key password cracking with `john`
- connection with SSH key and host exploration

## Topology summary
|Host|Image|Flavor|
|-|-|-|
|attacker|kali|csirtmu.tiny1x2|
|server|debian-10|csirtmu.tiny1x2|
|client|debian-10|csirtmu.tiny1x2|
|router|debian-10-x86_64|csirtmu.tiny1x2|


**Authors:** Benrebiai Oussama, Bey Abderrahim
