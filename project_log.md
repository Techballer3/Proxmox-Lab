# Proxmox Lab Project Log

## [2026-07-06]

### What I did
* Connected my Mini PC to my active home network.
* Configured the environment to run smoothly on the local network using DHCP.

### Why I did it
* **Accessibility:** Integrates seamlessly with your current working network setup without requiring extra manual static interface configurations.
* **Functionality:** Keeps everything running reliably and easily accessible on your active network.


## [2026-07-02]

### What I did
* Set up a new user account (`lab1`) for everyday tasks.
* Gave `lab1` "Administrator" permissions to manage the lab.
* Set up API Token authentication for the lab1 account.
* Enabled the firewall on my Proxmox host.

### Why I did it
* **Better Security:** It is safer to use a standard account for daily work.
* **Protection:** Saving the root account only for emergencies helps prevent mistakes and keeps the system more secure.
* **Easier Automation:** Using API tokens is safer and more secure than using a password for automated tasks.
* **Better Defense:** Turning on the firewall blocks unnecessary traffic, which helps keep the entire system safe.
