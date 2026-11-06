# Virtualization

## 1. Introduction

Virtualization is a technology that allows one physical computer to run multiple virtual computers using software.

Each virtual computer is called a Virtual Machine (VM). A VM behaves like a real computer and can run its own operating system, applications, and services.

Virtualization is useful in cybersecurity because it allows security professionals to create isolated environments for learning, testing, and security research.

## 2. What is a Virtual Machine?

A Virtual Machine is a software-based computer that uses the resources of a physical computer.

A VM can have:
- Virtual CPU
- Virtual RAM
- Virtual Hard Disk
- Virtual Network Adapter
- Virtual BIOS or UEFI

Example: Running Kali Linux inside VirtualBox on a Windows computer.

## 3. What is a Hypervisor?

A hypervisor is software that creates and manages virtual machines.

There are two main types.

### Type 1 – Bare Metal Hypervisor

Runs directly on physical hardware.

Examples:
- VMware ESXi
- Microsoft Hyper-V
- Xen

### Type 2 – Hosted Hypervisor

Runs as an application on an existing operating system.

Examples:
- Oracle VirtualBox
- VMware Workstation
- VMware Fusion

## 4. What is VirtualBox?

Oracle VirtualBox is a free and open-source virtualization application.

It allows users to create and run multiple operating systems on one physical computer.

Official website: https://www.virtualbox.org/

## 5. Virtual Machine Resources

When creating a VM, you can configure:

| Resource | Description |
|---|---|
| CPU | Processing power allocated to the VM |
| RAM | Memory allocated to the VM |
| Virtual Disk | Storage space for the VM |
| Network Adapter | Network connectivity |
| Display | Screen and graphics configuration |

## 6. What are VM Snapshots?

A snapshot saves the current state of a virtual machine.

It allows users to return to an earlier state if something goes wrong.

Benefits:
- Restore a working environment.
- Recover after configuration mistakes.
- Test software safely.
- Maintain a clean lab environment.

Important: A snapshot is not a complete backup. Keep separate backups of important files.

## 7. Virtual Networking

VirtualBox provides different networking modes.

| Mode | Description |
|---|---|
| NAT | VM accesses external networks through the host |
| Bridged Adapter | VM appears as a device on the physical network |
| Host-only Adapter | Communication between host and VMs on a private network |
| Internal Network | Communication between selected VMs |

For cybersecurity practice, Host-only and Internal Network modes are useful for creating isolated labs.

## 8. Importance in Offensive Security

Virtualization is useful for:
- Creating Kali Linux labs.
- Running intentionally vulnerable machines.
- Practicing penetration testing.
- Testing security tools.
- Creating isolated environments.
- Recovering lab machines using snapshots.

Always test against systems you own or have permission to assess.

## 9. Practical Assignment

1. Install Oracle VirtualBox.
2. Create a Kali Linux virtual machine.
3. Allocate suitable CPU and RAM resources.
4. Install and boot Kali Linux.
5. Create a snapshot named `Clean-Kali-Installation`.
6. Make a small configuration change.
7. Restore the snapshot.
8. Verify that the VM returns to its earlier state.

## 10. Conclusion

Virtualization provides a safe and flexible environment for learning operating systems and cybersecurity. Virtual machines and snapshots are essential tools for building an offensive security lab.

## 11. References

- https://www.virtualbox.org/
- https://www.kali.org/docs/virtualization/
- https://www.virtualbox.org/manual/
