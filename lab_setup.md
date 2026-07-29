# Lab Setup

* **Vulnerable Node:** Metasploitable (Running on Proxmox, IDE disk controller, isolated network bridge)
* **SIEM / Monitoring:** Wazuh server for centralized log management and intrusion detection
* **Attacking Node:** Kali Linux for security testing and validation
* **Network Security:** Network segmentation implemented to isolate lab traffic from the home network.

### Windows Lab VM
* **Platform:** Proxmox VE (Node: `pve`, VM ID: `105`)
* **OS:** Windows 10
* **Storage & Drivers:** Configured using VirtIO SCSI controller (`vioscsi`) and `virtio-win` ISO for optimized performance.
* **Network:** VirtIO Ethernet adapter (`netkvm`) configured for lab connectivity.
* **Upcoming:** Integration with Wazuh SIEM for centralized monitoring and log collection.
