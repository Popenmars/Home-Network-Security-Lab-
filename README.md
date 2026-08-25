# Home-Network-Security-Lab-
A hands-on SOC / Blue Team portfolio project covering network segmentation, firewall configuration, intrusion detection, SIEM deployment, and adversary simulation — built entirely on a virtualized home lab.

Overview

This project documents the design, build, and operation of a fully virtualized home SOC lab. Using VMware Workstation Pro, a small isolated network was constructed behind a pfSense firewall, populated with an attacker machine (Kali Linux) and two victim / monitored endpoints (Ubuntu Server and Windows 10). Network-layer intrusion detection was provided by Snort, host-layer detection and log correlation by a Wazuh SIEM deployment, and manual packet inspection by Wireshark. The project then progressed into live attack simulation — brute-force credential attacks, vulnerability scanning, and exploit research — to validate that each detection layer worked as intended, and to practice the analyst workflow of investigating and explaining what was found.
