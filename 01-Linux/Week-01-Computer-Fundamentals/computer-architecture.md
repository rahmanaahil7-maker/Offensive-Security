# Computer Architecture

## 1. Introduction

Computer architecture refers to the design and organization of a computer system. It explains how different hardware components work together to execute programs, process data, and store information.

Understanding computer architecture is important for cybersecurity because it helps us understand how operating systems, applications, memory, and hardware interact.

## 2. Main Components of a Computer

### 2.1 CPU (Central Processing Unit)

The CPU is the brain of the computer. It executes instructions and performs calculations.

Main components:
- **ALU (Arithmetic Logic Unit):** Performs mathematical and logical operations.
- **Control Unit:** Controls and coordinates CPU operations.
- **Registers:** Small, high-speed storage locations inside the CPU.

Useful command:

```bash
lscpu
```

### 2.2 RAM (Random Access Memory)

RAM temporarily stores data and instructions that are currently being used by running programs.

Characteristics:
- Volatile memory.
- Fast read and write operations.
- Data is lost when power is turned off.
- Used by operating systems and applications.

Useful command:

```bash
free -h
```

### 2.3 Storage

Storage devices permanently store operating systems, applications, and files.

Types:
- HDD (Hard Disk Drive)
- SSD (Solid State Drive)
- NVMe SSD

Unlike RAM, storage retains data even when the computer is powered off.

Useful command:

```bash
lsblk
```

### 2.4 Motherboard

The motherboard is the main circuit board that connects the CPU, RAM, storage, and other hardware components.

It allows different computer components to communicate.

### 2.5 GPU (Graphics Processing Unit)

The GPU processes graphics and performs parallel computations.

It is commonly used for:
- Gaming and graphics.
- Video processing.
- Machine learning.
- Certain password-cracking workloads.

## 3. How a Computer Processes Instructions

A computer generally follows these steps:

1. The user starts a program.
2. The operating system loads the required program instructions into RAM.
3. The CPU fetches instructions from memory.
4. The CPU decodes the instructions.
5. The CPU executes the instructions.
6. Results are stored in memory or written to storage.

This is commonly known as the Fetch–Decode–Execute cycle.

## 4. Types of Computer Architecture

### 4.1 32-bit Architecture

- Processes data using a 32-bit architecture.
- Has a smaller address space than 64-bit systems.
- Common in older computers.

### 4.2 64-bit Architecture

- Supports a much larger address space.
- Can efficiently handle large amounts of RAM.
- Common in modern computers.

Check your system architecture:

```bash
uname -m
```

## 5. Why Computer Architecture Matters in Cybersecurity

Understanding hardware and architecture helps security professionals understand:

- Memory management and memory vulnerabilities.
- Buffer overflow concepts.
- CPU architecture and executable formats.
- Operating system security.
- Virtual machines and isolation.
- How programs interact with hardware.

## 6. Practical Exercises

Run these commands in Kali Linux:

| Command | Purpose |
|---|---|
| `lscpu` | Display CPU information |
| `free -h` | Display RAM usage |
| `lsblk` | Display storage devices |
| `uname -m` | Display system architecture |
| `df -h` | Display disk usage |
| `sudo dmidecode -t system` | Display system information |

### Practical Observations

Record your results:

- CPU model:
- Number of CPU cores:
- Total RAM:
- Storage devices:
- System architecture:
- Operating system:

## 7. Conclusion

Computer architecture provides the foundation for understanding how computers operate. Knowledge of CPU, RAM, storage, and system architecture is essential for learning Linux, operating systems, and offensive security.

## 8. References

- https://www.geeksforgeeks.org/computer-organization-and-architecture-tutorials/
- https://www.kernel.org/doc/
- https://www.intel.com/content/www/us/en/developer/articles/technical/intel-sdm.html
