# Operating Systems

## 1. Introduction

An Operating System (OS) is system software that manages computer hardware and software resources.

It provides an interface between users, applications, and computer hardware.

Examples:
- Linux
- Windows
- macOS
- Android
- iOS

## 2. Main Functions of an Operating System

### 2.1 Process Management
Manages running programs and processes.

### 2.2 Memory Management
Allocates and manages RAM for running applications.

### 2.3 File Management
Organizes files and directories and controls file access.

### 2.4 Device Management
Manages hardware devices such as keyboards, disks, and network adapters.

### 2.5 Security Management
Controls user permissions, authentication, and access to system resources.

## 3. Kernel

The kernel is the core component of an operating system.

It communicates with hardware and manages:
- CPU scheduling
- Memory
- Processes
- Devices
- System calls

In Linux, the kernel is responsible for managing system resources.

Check the kernel version:

```bash
uname -r
```

## 4. Shell

A shell is a command interpreter that allows users to interact with the operating system.

Examples:
- Bash
- Zsh
- Fish

Check your current shell:

```bash
echo $SHELL
```

## 5. Linux vs Windows

| Feature | Linux | Windows |
|---|---|---|
| Source code | Mostly open source | Proprietary |
| Interface | CLI and GUI | GUI and CLI |
| File system | ext4, XFS, Btrfs | NTFS, ReFS |
| Security | Permissions and access controls | ACLs and access controls |
| Common usage | Servers, development, security | Desktop, enterprise |
| Customization | Highly customizable | More restricted |

## 6. Linux Distributions

A Linux distribution combines the Linux kernel with system tools, packages, and applications.

Examples:
- Kali Linux
- Ubuntu
- Debian
- Fedora
- Arch Linux

Kali Linux is designed for penetration testing and security auditing.

Official website: https://www.kali.org/

## 7. Important Linux System Commands

| Command | Purpose |
|---|---|
| `uname -a` | System information |
| `hostname` | Display hostname |
| `whoami` | Current username |
| `id` | User and group IDs |
| `uptime` | System uptime |
| `date` | Current date and time |
| `cat /etc/os-release` | OS information |
| `ps aux` | Running processes |
| `free -h` | Memory information |
| `df -h` | Disk information |

## 8. Why Operating Systems Matter in Cybersecurity

Understanding operating systems helps security professionals:
- Identify running services.
- Understand user permissions.
- Analyze running processes.
- Understand file system security.
- Identify misconfigurations.
- Learn privilege escalation concepts.
- Understand system-level vulnerabilities.

## 9. Practical Assignment

Execute these commands in Kali Linux:

```bash
uname -a
hostname
whoami
id
uptime
date
cat /etc/os-release
ps aux
free -h
df -h
```

Record your observations:

- Operating system:
- Kernel version:
- Current username:
- Hostname:
- System uptime:
- Available memory:
- Running processes:

## 10. Conclusion

An operating system manages hardware, applications, memory, processes, and security. Understanding Linux and Windows operating systems is a fundamental requirement for learning offensive security and penetration testing.

## 11. References

- https://www.kernel.org/doc/
- https://www.gnu.org/software/bash/manual/
- https://www.kali.org/docs/
