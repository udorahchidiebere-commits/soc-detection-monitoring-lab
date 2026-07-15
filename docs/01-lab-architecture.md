# Chapter 1 – Lab Architecture

## Objective

The objective of this chapter was to design and validate the architecture for a Security Operations Center (SOC) Detection and Monitoring Lab. This architecture provides an isolated environment for simulating cyberattacks, collecting logs, and performing security monitoring using Splunk Enterprise.

---

## Lab Environment

| Component | Purpose |
|-----------|---------|
| Host Machine | Windows 11 |
| Virtualization Platform | Oracle VirtualBox |
| Ubuntu Server | Splunk Enterprise (SIEM) |
| Windows 10 | Victim machine |
| Kali Linux | Attacker machine |

---

## Network Configuration

The virtual machines were configured to communicate over the same VirtualBox network, allowing attack simulations while maintaining network connectivity for log collection and analysis.

---

## Architecture Diagram

> Insert your architecture diagram here.

---

## Validation

The following checks were completed successfully:

- All virtual machines booted successfully.
- The virtual machines were connected to the same network.
- Network communication between the machines was verified.
- The lab environment was confirmed ready for software installation.

---

## Evidence

Include the following screenshots:

- VirtualBox Manager
- Ubuntu Server
- Windows 10
- Kali Linux
- Network configuration
- Successful connectivity tests

---

## Key Skills Gained

- VirtualBox virtualization
- SOC lab architecture design
- Network planning
- Windows and Linux virtual machine deployment

---

## Lessons Learned

Designing the lab architecture before installing software made it easier to understand the role of each virtual machine and how data will flow between the attacker, victim, and SIEM throughout the project.

---

## Conclusion

The lab environment has been successfully prepared and is ready for the installation and configuration of the remaining components, beginning with the operating systems and Splunk Enterprise.
