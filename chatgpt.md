# IGNOU MCS-022 — PYQ-Based Complete Study Guide

**Course:** MCS-022 — Operating System Concepts and Networking Management  
**Source analysed:** Uploaded merged PYQ PDF (`mcs22.pdf`), 36 pages  
**Papers identified:** June 2022, June 2023, December 2023, June 2024, December 2024, June 2025, December 2025, June 2026  
**Purpose:** Understand recurring concepts from the ground up and prepare to construct answers to unfamiliar question wording.

> **Important scope note:** This guide is based on the eight papers visible in the uploaded PDF. Frequency means that a broad topic or a clearly related subtopic occurs in a paper; it does not mean the exact same question was repeated. The paper set is not proof of what will appear in the next examination. Some questions refer specifically to older systems such as Windows 2000, Windows NT and Windows XP. Those historical details are retained where relevant to the PYQs rather than silently replaced with modern Windows behaviour.

---

# Table of Contents

1. [How to use this guide](#1-how-to-use-this-guide)
2. [PYQ analysis and priority ranking](#2-pyq-analysis-and-priority-ranking)
3. [Priority 1 — Linux commands, files, permissions and administration](#3-priority-1--linux-commands-files-permissions-and-administration)
4. [Priority 1 — Operating-system fundamentals and architecture](#4-priority-1--operating-system-fundamentals-and-architecture)
5. [Priority 1 — Computer security, authentication and cryptography](#5-priority-1--computer-security-authentication-and-cryptography)
6. [Priority 1 — Networking foundations, protocols and services](#6-priority-1--networking-foundations-protocols-and-services)
7. [Priority 1 — Windows administration, domains and network services](#7-priority-1--windows-administration-domains-and-network-services)
8. [Priority 2 — Network devices, topologies and transmission media](#8-priority-2--network-devices-topologies-and-transmission-media)
9. [Priority 2 — Storage, file systems, RAID and fault tolerance](#9-priority-2--storage-file-systems-raid-and-fault-tolerance)
10. [Priority 2 — Memory, processes and CPU utilisation](#10-priority-2--memory-processes-and-cpu-utilisation)
11. [Priority 3 — GUI, X-Windows and human-computer interaction](#11-priority-3--gui-x-windows-and-human-computer-interaction)
12. [Priority 3 — Other Windows and Linux administration topics](#12-priority-3--other-windows-and-linux-administration-topics)
13. [Important comparison tables](#13-important-comparison-tables)
14. [Diagrams to practise](#14-diagrams-to-practise)
15. [Rapid revision sheet](#15-rapid-revision-sheet)
16. [Seven-day study plan](#16-seven-day-study-plan)
17. [PYQ coverage checklist](#17-pyq-coverage-checklist)

---

# 1. How to use this guide

Do not try to memorise every paragraph. For each topic:

1. Read the explanation once to understand the idea.
2. Close the document and explain the idea aloud in your own words.
3. Reopen it and check what you missed.
4. Practise one or more PYQ variations listed at the end of the topic.
5. For a 10-mark question, practise writing a structured answer with an introduction, explanation, examples or diagram, and conclusion.

**What “understand a topic” means:** You should be able to explain what it is, why it is needed, how it works, its important types or components, and at least one example. If you can do that, you can usually adapt your answer when the examiner changes the wording.

## Priority labels

- **Priority 1 — Very high:** Broad area recurs throughout the paper set, or several distinct questions repeatedly test it.
- **Priority 2 — High:** Appears in multiple sessions and has clear exam relevance.
- **Priority 3 — Moderate:** Appears less consistently, often as a short note or a specialised question.
- **Priority 4 — Backup:** Isolated or relatively narrow question. Cover it after the higher priorities.

The labels are a study-time recommendation, not a prediction.

---

# 2. PYQ analysis and priority ranking

## 2.1 Papers identified

| Session | Main recurring areas visible in the paper |
|---|---|
| June 2026 | Linux commands and redirection, multiprogramming, TFTP, RAID, Windows printing and FRS, fsck, cryptography, filters and pipes, repeater, distributed OS, Kerberos, bus topology |
| December 2025 | Linux commands and permissions, firewall, FTP, GUI design, page replacement, buffering and spooling, system calls, THE system, Windows auditing, security risk analysis, modem, domains and DNS |
| June 2025 | Distributed OS, virtual memory, Windows services and registry, GUI, Linux date and administration, TCP/IP, DNS, VPN, topology, OS security, FAT-16/FAT-32, optical fibre, firewall |
| December 2024 | X-Windows, OS and multiprogramming, Linux features and home directory, peer-to-peer networking, Windows services, security goals and breaches, EFS, GUI, spooling, real-time OS, mesh topology, modem, DNS, FTP, cryptography, IPSec |
| June 2024 | Authentication, DNS components and configuration, OS features and components, OSI layers, router vs bridge, mapped drives, Windows domains and trust, Linux components and commands, VPN, Kerberos, fault tolerance, firewall, IP addressing, IDS, remote login, proxy |
| December 2023 | Linux commands, firewall, FAT/NTFS, X-Windows, packet switching, POP3/IMAP, transmission media, network topology, Apache setup, authentication, cryptography, security classification, system calls, virtual machines, WAN, VPN |
| June 2023 | Windows registry, firewall, RAID, Windows file systems, Linux paths and file permissions, Linux file and directory systems, Linux commands, Windows user/kernel modes, Kerberos, VPN, LAN/MAN/WAN, NTFS/EFS, gateways, Linux backup, distributed OS, user profiles |
| June 2022 | Linux commands and filters, Windows print spooler and permissions, RAID and striping, guided media, DTE/DCE, VPN, SNMP, shell scripting, multiprogramming vs multitasking, topology, security controls and backup, Windows user/kernel modes, Linux process/thread management, microkernel, auditing, group policy, Active Directory |

## 2.2 Priority matrix

The following counts are **paper-level broad-cluster counts**. A paper is counted when it contains at least one question or short note belonging to that broad area. Because some questions overlap, clusters are not mutually exclusive.

| Rank | Broad topic cluster | Papers containing related material | Priority |
|---:|---|---:|---|
| 1 | Linux commands, file handling, permissions or administration | 8/8 | **1** |
| 2 | Computer security, authentication or security controls | 8/8 | **1** |
| 3 | Networking protocols, services or network fundamentals | 8/8 | **1** |
| 4 | OS fundamentals, types, architecture or CPU/process management | 8/8 | **1** |
| 5 | Windows administration, security or network services | 8/8 | **1** |
| 6 | Network devices, topologies or transmission media | 8/8 | **1** |
| 7 | Storage, file systems, RAID or fault tolerance | 7/8 | **2** |
| 8 | GUI, X-Windows or interface design | 4/8 | **3** |

These are broad clusters. For example, “security” includes firewall, cryptography, authentication, Kerberos, auditing, EFS, IPSec, intrusion detection and security risk analysis. It does **not** mean each of those individual subtopics appeared in all eight papers.

## 2.3 High-value repeated subtopics

| Subtopic | Evidence in the uploaded papers | Study recommendation |
|---|---|---|
| Linux commands | Command-use questions in June 2022, June 2023, June 2024, December 2025 and June 2026; related Linux file/permission questions in other sessions | Learn commands by purpose and practise writing exact syntax |
| Linux permissions and file system | June 2023, December 2025, June 2026, plus Linux file-management questions elsewhere | Very high |
| Firewall | December 2023, June 2024, June 2025, December 2025; firewall-related short note in December 2024 | Very high |
| VPN | June 2022, June 2023, June 2024, June 2025; related remote-access concepts | Very high |
| Kerberos | June 2023, June 2024, June 2026 | Very high |
| DNS | December 2024, June 2025, June 2024 | Very high |
| Cryptography/authentication | December 2023, June 2024, December 2024, June 2026, and authentication-related questions in other sessions | Very high |
| Network topology | June 2022, December 2023, December 2024, June 2025, June 2026 | Very high |
| Multiprogramming / CPU utilisation | June 2022, December 2024, December 2025, June 2026 | High |
| Windows domains, users and trust | June 2023, June 2024, June 2025, December 2025, June 2026 | High |
| RAID / mirroring / striping | June 2022, June 2023, June 2026 | High |
| FAT / NTFS / EFS | June 2023, December 2023, June 2025 | High |
| Modems | December 2024, December 2025 | Moderate-high |
| X-Windows | December 2023, December 2024 | Moderate |
| Distributed OS | June 2023, June 2025, June 2026 | High |

**Key takeaway:** Start with Linux, security, networking, OS fundamentals and Windows administration. They cover a large share of the recurring syllabus. Do not skip RAID, DNS, VPN, Kerberos, topology or Windows domains.

---

# 3. Priority 1 — Linux commands, files, permissions and administration

Linux is an operating system. It provides a way for users and programs to interact with hardware, manage files, run processes and communicate with other systems. In the exam, Linux is tested very practically: commands, permissions, paths, filters, pipes, file-system consistency and system administration.

## 3.1 Linux file-system structure

A file system is the method an operating system uses to organise and store files on a storage device. Linux presents files and directories in a single tree structure beginning at `/`, called the root directory.

Unlike a Windows-style arrangement where drives are commonly shown as `C:` or `D:`, Linux attaches storage devices into the existing directory tree through **mount points**.

Common directories:

| Directory | Purpose |
|---|---|
| `/` | Root of the entire file-system hierarchy |
| `/home` | Home directories of ordinary users |
| `/root` | Home directory of the root administrator |
| `/etc` | System-wide configuration files |
| `/bin` | Essential user commands (on systems using merged `/usr`, this may be linked to `/usr/bin`) |
| `/sbin` | Essential system-administration commands (may be linked into `/usr` on modern systems) |
| `/var` | Frequently changing data such as logs, spool files and caches |
| `/tmp` | Temporary files |
| `/dev` | Device files representing devices |
| `/proc` | Virtual file system exposing process and kernel information |
| `/boot` | Files needed to start the operating system |
| `/usr` | Applications, libraries, documentation and other user-space software |

A **home directory** is the personal working directory assigned to a user. For example, `/home/rahul` may contain that user's documents and personal files. The `~` symbol usually represents the current user's home directory.

### Absolute and relative paths

An **absolute path** begins at the root `/` and describes the full location, such as `/home/rahul/notes.txt`.

A **relative path** is interpreted from the current working directory. If the current directory is `/home/rahul`, then `Documents/notes.txt` refers to `/home/rahul/Documents/notes.txt`.

Useful symbols:
- `.` means the current directory.
- `..` means the parent directory.
- `~` means the current user's home directory.

## 3.2 Essential Linux commands

Learn what each command does, its basic syntax and a small example. A question may ask you to write a command, explain its output or state its purpose.

| Command | Purpose | Example |
|---|---|---|
| `pwd` | Displays current working directory | `pwd` |
| `ls` | Lists directory contents | `ls -l` |
| `ls -a` | Includes hidden files | `ls -a` |
| `ls -F` | Adds indicators such as `/` after directory names | `ls -F` |
| `cd` | Changes directory | `cd /home/user` |
| `mkdir` | Creates a directory | `mkdir notes` |
| `rmdir` | Removes an empty directory | `rmdir notes` |
| `touch` | Creates an empty file or updates its timestamp | `touch a.txt` |
| `cat` | Displays or combines file contents | `cat a.txt` |
| `head` | Displays the beginning of a file; default is 10 lines | `head -n 5 a.txt` |
| `tail` | Displays the end of a file; default is 10 lines | `tail -n 10 a.txt` |
| `cp` | Copies files or directories | `cp a.txt b.txt` |
| `mv` | Moves or renames a file | `mv old.txt new.txt` |
| `rm` | Removes files | `rm a.txt` |
| `grep` | Searches text matching a pattern | `grep "error" log.txt` |
| `wc` | Counts lines, words and bytes/characters | `wc -l a.txt` |
| `cmp` | Compares two files byte by byte | `cmp a.txt b.txt` |
| `diff` | Shows line-based differences between files | `diff a.txt b.txt` |
| `tree` | Displays directory structure as a tree, if installed | `tree` |
| `ps` | Displays process information | `ps -ef` |
| `kill` | Sends a signal to a process, commonly to request termination | `kill 1234` |
| `who` | Shows users currently logged in | `who` |
| `date` | Displays or sets date/time, subject to permissions | `date` |
| `man` | Opens a command's manual page | `man ls` |
| `chmod` | Changes file permissions | `chmod 640 a.txt` |
| `fsck` | Checks and may repair a file system | `fsck /dev/device` |
| `wall` | Broadcasts a message to logged-in users' terminals | `wall "System maintenance"` |
| `write` | Sends a message to a particular logged-in user | `write user1` |

### Useful command patterns from the papers

```bash
cat file-1 file-2 file-3
```
Displays the contents of the three files in the terminal.

```bash
ls -F
```
Lists entries and appends `/` to directory names.

```bash
tail -n +17 file.txt
```
Prints the file starting from line 17.

```bash
tail -n 10 file.txt
```
Prints the last ten lines.

```bash
who
```
Displays logged-in users.

```bash
ps -ef
```
Displays a detailed list of processes.

```bash
chmod 400 sample.txt
```
Gives the owner read permission and removes group/other permissions. Another valid symbolic form is `chmod u=r,go= sample.txt`.

```bash
ls -a
```
Lists hidden entries as well as ordinary entries. In Linux, names beginning with `.` are hidden by convention.

### Redirection

Normally, a command displays output on the terminal. **Redirection** changes where that output goes.

Linux commonly uses:
- Standard input: file descriptor `0`
- Standard output: file descriptor `1`
- Standard error: file descriptor `2`

Examples:

```bash
command > out-file
command 2> err-file
command > one-file 2>&1
```

The first sends normal output to `out-file`. The second sends error messages to `err-file`. The third sends both standard output and standard error to the same file. The order matters: `> one-file 2>&1` first redirects standard output, then sends standard error to the same destination.

`>` overwrites a file. `>>` appends to it.

## 3.3 File permissions

Linux permissions determine who can read, change or execute a file. There are three classes of users:

- **Owner (u):** The user who owns the file.
- **Group (g):** Users belonging to the file's group.
- **Others (o):** Everyone else.

There are three basic permissions:

| Permission | On a regular file | On a directory |
|---|---|---|
| Read (`r`) | View file contents | List directory entries |
| Write (`w`) | Modify file contents | Create, delete or rename entries, subject to other controls |
| Execute (`x`) | Run the file as a program/script | Enter/traverse the directory |

A directory's execute permission is not the same as executing a program. It means being able to traverse/search that directory.

### Numeric permission notation

Permissions are represented by numbers:
- Read = 4
- Write = 2
- Execute = 1

Add the values for each user class.

Example: `chmod 754 file.sh`
- Owner: 7 = read + write + execute
- Group: 5 = read + execute
- Others: 4 = read only

Example: `chmod 600 secret.txt` gives the owner read/write and gives no permissions to group or others.

### Why permissions matter

Permissions protect private data, prevent unauthorised changes and limit who can execute programs. They are a basic part of multi-user operating-system security.

## 3.4 Filters and pipelines

A **filter** is a command that reads input, processes it and produces output. Many Linux commands can be used as filters.

Examples:
- `grep` selects lines matching a pattern.
- `sort` sorts lines.
- `wc` counts lines, words or characters.
- `head` selects the beginning of input.
- `tail` selects the end of input.

A **pipeline** connects the output of one command to the input of another using `|`.

```bash
cat marks.txt | sort | head -n 5
```

Conceptually:
1. `cat` sends file contents to standard output.
2. The pipe sends that output to `sort`.
3. `sort` produces sorted lines.
4. The next pipe sends them to `head`.
5. `head` displays the first five lines.

A pipeline avoids the need to save every intermediate result in a separate file.

## 3.5 File-system consistency and `fsck`

A file system stores information about files, directories, free space and the relationship between them. A sudden shutdown or storage error can leave some of this information inconsistent.

**`fsck` (file system check)** is a family of utilities used to check and, where possible, repair file-system inconsistencies.

It can detect problems such as:
- Incorrect metadata.
- Invalid directory references.
- Inconsistent allocation information.
- Orphaned file-system objects.

It may ask whether to repair detected problems. The exact behaviour depends on the file-system type and tool.

**Important safety point:** A file system should generally be unmounted before a manual repair check. Running a repair on a mounted, actively changing file system can cause damage. Modern Linux systems may use file-system-specific check tools underneath `fsck`.

## 3.6 Device files

Linux represents many devices through special files, commonly found under `/dev`. A program can interact with a device using file-like operations.

Two classic types:
- **Character device:** Transfers data as a stream of characters/bytes, often sequentially. Examples traditionally include terminals and serial ports.
- **Block device:** Transfers data in blocks and supports block-oriented storage access. Examples include disks.

Device files are not ordinary documents containing the device's data. They are interfaces through which the kernel and device drivers provide access to hardware.

## 3.7 `wall` and `write`

- `wall` sends a message to all users who are currently logged in and whose terminals permit messages.
- `write` sends a message to a particular logged-in user.

These are useful for system announcements. `wall` is normally associated with administrative/system-wide announcements; ordinary users may be restricted by system configuration and terminal permissions.

## 3.8 Linux system administration

A Linux system administrator is responsible for keeping the system usable, secure and reliable. Common duties include:
- Creating, modifying and deleting user accounts.
- Managing groups and permissions.
- Installing and updating software.
- Monitoring processes and system resources.
- Managing storage, file systems and backups.
- Configuring network services.
- Checking logs and investigating failures.
- Applying security updates and controlling access.

## PYQ connection

Questions in the uploaded papers include:
- Linux command purposes and command output (June 2022, June 2023, June 2024, December 2025, June 2026).
- Hidden files, processes, permissions, last lines and logged-in users (December 2023).
- Absolute and relative pathnames; file and directory systems; permission modes (June 2023).
- Read, write and execute permissions on files and directories (December 2025).
- Filters and pipelines (June 2022, June 2026).
- `fsck` and device files (June 2026).
- Linux system administration and account management (June 2025).

**What the examiner is testing:** Whether you understand the Linux command-line environment, can choose a suitable command, understand permissions and explain how Linux organises and protects files.

**How to construct a 5-mark answer:** Define the concept, explain its purpose, list the main points and give one correct command/example.

**How to construct a 10-mark answer:** Introduce the concept, explain its components or working step by step, add syntax/examples or a small diagram, and finish with its uses or importance.

---

# 4. Priority 1 — Operating-system fundamentals and architecture

## 4.1 What is an operating system?

An **operating system (OS)** is system software that manages computer hardware and provides services to application programs and users.

A computer has hardware such as the CPU, memory, storage and input/output devices. Applications need a controlled way to use these resources. The operating system acts as the manager between applications/users and hardware.

Without an OS, every application would need to manage hardware directly, which would be difficult, unsafe and inefficient.

### Main objectives

1. **Convenience:** Makes the computer easier to use.
2. **Efficiency:** Uses CPU, memory and devices effectively.
3. **Resource management:** Allocates resources among competing programs.
4. **Protection and security:** Controls access to data and system resources.
5. **Ability to evolve:** Provides a structure for adding features and supporting new hardware.

### Main components

| Component | What it does |
|---|---|
| Process management | Creates, schedules and terminates processes |
| Memory management | Tracks and allocates RAM |
| File-system management | Organises files and directories |
| Device/I/O management | Controls input/output devices through drivers |
| Secondary-storage management | Manages disks and storage allocation |
| Security/protection | Controls access and isolates users/processes |
| User interface | Allows interaction through command line or GUI |
| Networking | Supports communication between computers |

## 4.2 Types of operating systems

### Batch operating system

Jobs are collected and processed in batches, with little or no interaction from the user while a job is running. Historically useful for repetitive, large-scale processing.

### Multiprogramming operating system

Several programs are kept in memory at the same time. When one program waits for an I/O operation, the CPU can execute another ready program.

**Why it improves performance:** A program may spend time waiting for a disk, keyboard or other device. If the CPU did nothing during that wait, it would be wasted. Multiprogramming allows another program to use the CPU during that period.

### Multitasking / time-sharing

The CPU switches rapidly among tasks, often giving each task a small time slice. This creates the impression that multiple programs are running simultaneously.

A time-sharing system is designed to provide interactive response to multiple users or tasks.

### Real-time operating system (RTOS)

A real-time OS is designed to respond to events within specified timing constraints. Correctness depends not only on the result but also on producing it at the required time.

- **Hard real-time:** Missing a deadline is considered system failure.
- **Soft real-time:** Missing an occasional deadline reduces quality but may not cause total failure.

Applications include industrial control, embedded systems, medical monitoring and control systems. Not every system used in a time-sensitive environment is automatically a hard real-time system.

### Distributed operating system

A distributed OS manages a collection of network-connected computers and aims to make their resources appear to users as part of a coordinated system.

Important characteristics:
- Resource sharing.
- Communication between machines.
- Distribution of processing and data.
- Coordination of tasks.
- Transparency, where the system hides some details of where resources are located.
- Reliability and potential fault tolerance.

A distributed OS is different from simply having computers connected to a network. It provides system-level coordination across multiple machines.

### Network operating system

A network OS provides services that allow independent computers to communicate and share resources such as files, printers and user accounts. Each machine may remain visibly distinct to the user.

### Virtual machine system

A virtual machine (VM) is a software-created computer environment that behaves like a separate computer. A hypervisor or virtual-machine monitor manages the underlying hardware and allocates resources to virtual machines.

VMs can run separate operating-system instances on one physical machine, supporting isolation, testing and server consolidation.

## 4.3 Multiprogramming, multitasking, buffering and spooling

These terms are related because they improve resource utilisation, but they solve different problems.

### Buffering

A **buffer** is a temporary memory area used while data moves between devices or between a device and a program.

Why it is needed: A CPU and an I/O device may operate at different speeds. A buffer helps smooth the transfer and reduces the need for the CPU or program to wait for every small transfer.

Example: Data can be collected in a memory buffer before being written to a slower device.

### Spooling

**Spooling** means placing jobs in a queue, commonly on disk, so a device can process them one at a time.

Example: Several users send documents to a printer. The print-spooler stores the jobs in a queue. The printer processes each job when it becomes available.

### Multiprogramming

Keeps multiple programs ready in memory so the CPU can switch to another when one waits.

### Quick distinction

- Buffering: temporary holding area for data transfer.
- Spooling: queue of jobs for a shared device.
- Multiprogramming: multiple programs in memory so CPU time is not wasted.
- Multitasking: CPU switches among tasks to provide concurrent execution/interaction.

## 4.4 User mode and kernel mode

Modern operating systems distinguish between less-privileged execution and privileged operating-system execution.

**User mode:** Ordinary applications run with restricted privileges. They cannot directly execute every privileged hardware instruction or freely access kernel memory.

**Kernel mode:** The operating-system kernel runs with high privilege. It manages hardware, memory, processes and protected resources.

When an application needs a protected service, it requests it through a **system call**. The CPU changes to kernel mode, the kernel performs the requested operation after checking it, and control returns to user mode.

This separation improves stability and security. A faulty ordinary application should not be able to directly overwrite critical kernel memory.

The Windows 2000 papers specifically ask about the roles and responsibilities of user mode and kernel mode. For an exam answer, explain the purpose of the separation, the responsibilities of each mode and how a system call crosses the boundary.

## 4.5 System calls

A **system call** is a controlled interface through which a user program requests a service from the operating-system kernel.

Common categories:
- Process control: create, execute or terminate processes.
- File management: open, read, write and close files.
- Device management: request or release devices.
- Information maintenance: obtain time or system information.
- Communication: exchange data between processes.

A typical file-copy program conceptually:
1. Opens the source file.
2. Creates or opens the destination file.
3. Reads a block from the source.
4. Writes the block to the destination.
5. Repeats until the end of the source.
6. Closes both files.

The exact system-call names vary by operating system and programming interface. On Unix-like systems, common calls include `open`, `read`, `write` and `close`.

## 4.6 Process and thread management

A **program** is a set of instructions stored on disk. A **process** is a program in execution, with its own execution state and resources.

A process commonly has:
- Process identifier (PID).
- Current state.
- Program counter.
- CPU register state.
- Memory address space.
- Open files and other resources.

Typical process states:
- New: being created.
- Ready: able to run, waiting for CPU.
- Running: currently executing.
- Waiting/Blocked: waiting for an event or I/O.
- Terminated: finished execution.

A **thread** is a unit of execution within a process. Threads in the same process share much of the process's memory and resources, but each thread has its own execution state and stack.

Threads can improve responsiveness and allow work to proceed concurrently, but shared data must be coordinated carefully to avoid race conditions.

## 4.7 Operating-system architectures

### Monolithic kernel

Many core operating-system services run in kernel space. This can provide efficient communication between components, but a fault in a kernel component can affect the whole system.

### Microkernel

A microkernel keeps the kernel small, retaining only essential mechanisms such as basic scheduling, low-level memory management and inter-process communication. Other services may run as separate user-space processes.

Potential advantages:
- Smaller trusted kernel.
- Better isolation of services.
- Easier to replace or restart some services.

Potential disadvantages:
- Communication between components may add overhead.
- Design and coordination can be more complex.

### Layered architecture

The OS is divided into layers. Each layer uses services from the layer below and provides services to the layer above. This makes the design easier to understand and maintain, although strict layering can introduce overhead or restrictions.

### THE operating system

The “THE” system is a classic layered operating-system design associated with Edsger Dijkstra. It is commonly described as having six layers, from hardware at the bottom through basic process/memory management and higher-level operator/user interaction. The exact layer names should be learnt from the course material if your textbook gives a specific list; the PYQ asks students to list and explain the six layers.

## PYQ connection

Questions include:
- OS definition, features and components (June 2024).
- OS and multiprogramming (December 2024).
- Multiprogramming vs multitasking (June 2022).
- Buffering, spooling and CPU utilisation (December 2025; spooling also December 2024).
- Distributed OS (June 2023, June 2025, June 2026).
- Real-time OS (December 2024).
- System calls (June 2022, December 2023, December 2025).
- User mode vs kernel mode (June 2022 and June 2023).
- Process and thread management (June 2022).
- Microkernel and THE system (June 2022, December 2025).

**Exam construction:** For a 10-mark OS question, define the OS, explain its purpose, describe relevant components or types, include a labelled diagram if suitable, and finish with the benefits or applications. For comparison questions, compare on the same dimensions rather than writing two unrelated paragraphs.

---

# 5. Priority 1 — Computer security, authentication and cryptography

Security appears in many forms in the papers. Do not study “security” as one memorised answer. Understand the goals, threats, controls and mechanisms, then learn the named technologies.

## 5.1 Goals of computer security

The classic security goals are often described using the CIA triad:

1. **Confidentiality:** Information is accessible only to authorised people.
2. **Integrity:** Information is not changed improperly; changes should be authorised and detectable.
3. **Availability:** Systems and information remain accessible when needed.

Other important goals:
- Authentication: proving an identity.
- Authorisation: deciding what an authenticated identity may do.
- Accountability/auditing: recording actions so they can be traced.
- Non-repudiation: providing evidence that a party performed an action, where the system and legal context support it.

Do not confuse authentication with authorisation. Logging in proves or establishes identity; permissions determine what that identity can access.

## 5.2 Threats and security breaches

A security threat is a possible cause of harm. A vulnerability is a weakness that may be exploited. An attack is an attempt to exploit a weakness. A breach is an incident in which security is violated.

Common categories:
- **Interruption:** A resource becomes unavailable (availability attack).
- **Interception:** An unauthorised party accesses information (confidentiality attack).
- **Modification:** Data is changed without authorisation (integrity attack).
- **Fabrication:** False data or activity is introduced (authenticity/integrity issue).

Examples include malware, password theft, unauthorised access, denial of service, data tampering and eavesdropping.

## 5.3 User authentication methods

Authentication answers: “Are you really the person or system you claim to be?”

Common factors:

| Factor | Meaning | Example |
|---|---|---|
| Something you know | Secret knowledge | Password or PIN |
| Something you have | Possession of an item | Smart card, hardware token |
| Something you are | Biometric characteristic | Fingerprint or face recognition |
| Somewhere you are | Location context | Access from an approved location |
| Something you do | Behavioural pattern | Typing rhythm, where implemented |

**Multi-factor authentication (MFA)** combines two or more different factor categories. Two passwords are not true multi-factor authentication because both are “something you know”.

Other authentication approaches include:
- Password-based authentication.
- Challenge-response authentication.
- One-time passwords.
- Smart cards and tokens.
- Biometric authentication.
- Certificate-based authentication.
- Kerberos ticket-based network authentication.

## 5.4 Cryptography

Cryptography protects information by transforming readable data (plaintext) into an unreadable form (ciphertext) using an algorithm and key.

Basic flow:

```text
Plaintext --encryption + key--> Ciphertext
Ciphertext --decryption + key--> Plaintext
```

The algorithm describes the mathematical procedure; the key is the value that controls the transformation. Security should depend on keeping keys protected, not on keeping a sound algorithm secret.

### Symmetric-key cryptography

The same secret key, or closely related secret key material, is used for encryption and decryption.

Advantages:
- Fast and efficient for large amounts of data.
- Suitable for bulk encryption.

Challenges:
- Sender and receiver must securely obtain the shared secret.
- Key distribution and key management become difficult as the number of users grows.

Example algorithm: AES.

### Asymmetric-key cryptography

Uses a mathematically related key pair:
- Public key: can be shared.
- Private key: must be kept secret.

A message encrypted with the recipient's public key can be decrypted by the corresponding private key. Digital-signature systems use the private key to create a signature that can be verified with the public key.

Advantages:
- Helps with key exchange and identity verification.
- Supports digital signatures.

Challenges:
- More computationally expensive than symmetric encryption.
- Requires trustworthy binding between public keys and identities, commonly through certificates and a public-key infrastructure.

Example algorithm family: RSA; elliptic-curve systems are also widely used.

### Hybrid encryption

Real systems often combine both approaches. Asymmetric cryptography helps establish or protect a session key, and symmetric cryptography encrypts the bulk data efficiently.

## 5.5 Digital signatures and certificates

A digital signature provides a way to verify that data was signed by the holder of a private key and that the signed data has not been altered, assuming the cryptographic system and key handling are sound.

A simplified process:
1. The sender calculates a hash of the message.
2. The sender signs the hash using their private key.
3. The receiver checks the signature using the corresponding public key.
4. The receiver independently hashes the received message and compares the results.

A digital certificate binds a public key to an identity and is signed by a trusted certificate authority (CA). The receiver checks the certificate chain and validity.

## 5.6 Kerberos authentication

Kerberos is a network authentication protocol that uses secret-key cryptography and tickets to authenticate users to network services without repeatedly sending the user's password across the network.

Main components:
- **Client:** User or machine requesting a service.
- **Authentication Server (AS):** Initially verifies the client and issues a Ticket-Granting Ticket (TGT).
- **Ticket-Granting Server (TGS):** Uses the TGT to issue a service ticket.
- **Service server:** The network service the client wants to access.
- **Key Distribution Center (KDC):** The trusted Kerberos authority, commonly consisting of AS and TGS functions.

Simplified process:

```text
Client -> AS: Request initial authentication
AS -> Client: Ticket-Granting Ticket (TGT)
Client -> TGS: TGT + request for a particular service
TGS -> Client: Service ticket
Client -> Service: Service ticket
Service -> Client: Access after ticket validation
```

The TGT lets the client request tickets for services without entering the password for every service. Kerberos relies on a trusted authority and generally requires clocks to be sufficiently synchronised because tickets have validity periods.

**Why tickets matter:** They allow the system to authenticate a client to services while reducing repeated password transmission.

## 5.7 Firewall

A firewall is a security system that monitors and controls network traffic according to a defined security policy. It creates a boundary between networks or systems with different trust levels.

### Packet-filtering firewall

Examines packet information such as source/destination IP address, port and protocol. It allows or blocks traffic according to rules.

Advantages:
- Relatively simple.
- Can be efficient.
- Useful for enforcing basic network access rules.

Limitations:
- Basic filters may not understand application-level meaning.
- A permitted port does not guarantee that the application traffic is safe.
- Rule design and maintenance can be difficult.

### Proxy / application-level firewall

A proxy acts as an intermediary between a client and a destination service. The client connects to the proxy, and the proxy makes or manages the onward connection.

Advantages:
- Can inspect application-level requests.
- Can hide internal client details from external servers.
- Can enforce application-specific rules and logging.

Limitations:
- May introduce latency.
- Requires proxy support/configuration.
- Can become a bottleneck or point of failure.

### Firewall limitations

A firewall cannot by itself:
- Stop every attack originating inside the trusted network.
- Protect a device from all malware or unsafe user actions.
- Fix weak passwords or insecure application code.
- Guarantee safety if rules are misconfigured.
- Protect data after it has been legitimately accessed and copied elsewhere.

A firewall is one layer in a broader security strategy.

## 5.8 VPN and IPSec

A **Virtual Private Network (VPN)** creates a protected logical connection over an untrusted or shared network such as the Internet.

Why use it?
- Remote employees can access an organisation's internal network.
- Two office networks can communicate securely.
- Traffic can be protected while travelling over a public network.

VPN protection may include encryption, authentication and integrity checking. A VPN is not automatically anonymous and does not make an insecure endpoint safe.

### Common VPN categories

- Remote-access VPN: connects an individual user/device to an organisation.
- Site-to-site VPN: connects two networks, often office-to-office.

### IPSec

IPSec is a suite of protocols for protecting IP communication. Important concepts:
- **AH (Authentication Header):** Provides integrity and data-origin authentication, but not encryption.
- **ESP (Encapsulating Security Payload):** Can provide confidentiality through encryption and can also provide integrity/authentication.
- **Transport mode:** Protects the IP payload while retaining the original IP header.
- **Tunnel mode:** Protects the entire original IP packet by encapsulating it inside a new IP packet; commonly used in gateway-to-gateway VPNs.
- **IKE (Internet Key Exchange):** Negotiates security associations and keys.

## 5.9 EFS, auditing, intrusion detection and risk analysis

### EFS (Encrypting File System)

EFS is a Windows file-encryption feature associated with NTFS. It encrypts selected files so that unauthorised users who obtain the storage media cannot simply read the file contents.

EFS is distinct from full-disk encryption: it focuses on files/folders and uses user-associated encryption keys. Key backup and recovery are important; losing the necessary private key or recovery material can make encrypted data inaccessible.

### Auditing

Auditing records selected security-related events, such as logon attempts, access to objects or changes to security settings. It supports:
- Detecting suspicious activity.
- Investigating incidents.
- Establishing accountability.
- Checking whether security policies are being followed.

Auditing does not automatically prevent an attack. It provides records that help detection and investigation.

### Intrusion Detection System (IDS)

An IDS monitors system or network activity for suspicious behaviour or policy violations and raises alerts.

- Network-based IDS (NIDS): monitors network traffic.
- Host-based IDS (HIDS): monitors activity on an individual machine.

An IDS primarily detects and alerts. An intrusion prevention system (IPS) may also take action to block activity.

### Security risk analysis

A simple risk-analysis process:
1. Identify assets, threats and vulnerabilities.
2. Estimate likelihood and impact of each risk.
3. Prioritise risks and choose controls to reduce, transfer, avoid or accept them.

A risk is not just a vulnerability. It combines the chance of something happening with the harm it could cause.

## PYQ connection

The papers ask about:
- Authentication methods (June 2023, June 2024, December 2023 and related security questions).
- Symmetric vs asymmetric cryptography (December 2023, June 2026).
- Cryptography and alternatives to cryptography-based authentication (December 2024, June 2026).
- Kerberos and client authentication (June 2023, June 2024, June 2026).
- Firewall operation and limitations (December 2023, June 2024, June 2025, December 2025; also a short note in December 2024).
- VPN and its security/protocols/configuration (June 2022, June 2023, June 2024, June 2025).
- EFS, IPSec, auditing, IDS, security breach, security goals and risk analysis across several sessions.

**10-mark answer approach:** Define the security concept, state the problem it solves, explain the mechanism step by step, describe its components or types, discuss benefits and limitations, and include a flow diagram if the mechanism has stages.

---

# 6. Priority 1 — Networking foundations, protocols and services

A computer network is a collection of connected devices that exchange data and share resources. Devices communicate using agreed rules called **protocols**.

## 6.1 Communication protocols

A protocol defines rules for communication, including:
- Format of messages.
- Meaning of fields.
- Timing and sequencing.
- Error detection or recovery.
- Addressing and delivery.

Without common protocols, devices would not know how to interpret one another's messages.

Examples:
- IP: addressing and routing packets.
- TCP: reliable, ordered transport.
- UDP: connectionless transport with low overhead.
- HTTP/HTTPS: web communication.
- FTP: file transfer.
- DNS: name resolution.
- SMTP: sending email.
- POP3/IMAP: retrieving and accessing email.

## 6.2 TCP/IP

TCP/IP is the family of protocols used by the Internet and many private networks.

A common four-layer model:

| Layer | Main responsibility | Examples |
|---|---|---|
| Application | Services used by applications | HTTP, FTP, DNS, SMTP |
| Transport | End-to-end process communication | TCP, UDP |
| Internet | Logical addressing and routing | IP, ICMP |
| Network access/link | Local delivery over the physical/link technology | Ethernet, Wi-Fi |

### TCP

TCP is connection-oriented and provides a reliable, ordered byte stream. It uses acknowledgements, sequence numbers, retransmission and flow/congestion-control mechanisms.

### UDP

UDP is connectionless and provides datagrams without guaranteeing delivery, ordering or retransmission. It has lower protocol overhead and is useful where applications prefer speed or handle recovery themselves.

## 6.3 FTP and TFTP

### FTP (File Transfer Protocol)

FTP is an application-layer protocol for transferring files between a client and server.

Traditional FTP uses:
- A control connection, commonly TCP port 21.
- A separate data connection. The exact connection setup differs between active and passive modes.

FTP supports operations such as listing directories, uploading and downloading files, subject to account permissions.

Traditional FTP does not encrypt credentials or file contents. Secure alternatives include SFTP (over SSH) and FTPS (FTP protected by TLS); these are different protocols/approaches.

### TFTP (Trivial File Transfer Protocol)

TFTP is a simpler file-transfer protocol. It uses UDP and has a small command set, traditionally supporting read and write requests. It does not provide the richer authentication and directory-management capabilities of FTP.

Common uses include transferring boot files, firmware or configuration files in controlled local environments, such as network-device bootstrapping.

| FTP | TFTP |
|---|---|
| Uses TCP | Uses UDP |
| More feature-rich | Very simple |
| Supports user authentication in traditional implementations | No built-in user authentication |
| Separate control/data behaviour | Simple request/data/acknowledgement exchanges |
| Used for general file transfer | Often used for boot/configuration transfer in controlled networks |

## 6.4 DNS (Domain Name System)

People find names such as `example.com` easier to remember than numeric IP addresses. DNS is a distributed naming system that translates domain names into records such as IP addresses and provides other naming information.

### How DNS resolution works

1. A user enters a domain name.
2. The client checks local/browser/OS caches.
3. If needed, it asks a configured recursive resolver.
4. The resolver may query the DNS hierarchy: root, top-level domain (TLD), then authoritative server.
5. The authoritative server provides the requested record.
6. The resolver returns the answer and may cache it according to its TTL.

Simplified hierarchy:

```text
                 Root DNS
                    |
             TLD DNS (.com)
                    |
          Authoritative DNS
                    |
             example.com
                    |
                IP address
```

### Important DNS components and terms

- **Resolver:** Finds answers on behalf of a client.
- **Recursive resolver:** Takes responsibility for obtaining the answer.
- **Root server:** Directs the resolver toward the relevant TLD.
- **TLD server:** Directs the resolver toward authoritative servers for a domain.
- **Authoritative server:** Holds the official DNS records for a zone.
- **Zone:** Administrative portion of the DNS namespace.
- **Resource record:** A record containing DNS information.
- **TTL:** Time-to-live, which controls how long a cached record may be retained.

Common records:
- A: IPv4 address.
- AAAA: IPv6 address.
- CNAME: alias to another name.
- MX: mail exchanger.
- NS: name server.
- TXT: text information, often used for verification and email policies.
- PTR: reverse lookup.

### DNS design goals

DNS is designed to be distributed, scalable, reliable and efficient. Caching reduces repeated queries. Hierarchical delegation distributes administration rather than relying on one central database.

### Configuring DNS in Linux — conceptual steps

The exact commands depend on the Linux distribution and DNS server software. A safe conceptual answer:
1. Choose and install DNS server software, such as BIND if the course expects it.
2. Configure the server's listening interfaces and options.
3. Define the DNS zone and its records.
4. Check syntax/configuration.
5. Start or reload the service.
6. Permit DNS traffic through the firewall.
7. Test resolution with tools such as `dig` or `nslookup`.
8. Configure clients to use the resolver.

Do not blindly copy commands from a different Linux distribution; service names and configuration paths vary.

## 6.5 POP3 and IMAP

Both are email-retrieval protocols.

- **POP3:** Traditionally downloads messages from the mail server to a client. Depending on settings, messages may be removed from the server or retained.
- **IMAP:** Keeps mail organised on the server and synchronises folders and message state across devices.

IMAP is generally better when a user checks the same mailbox from several devices. POP3 is simpler and may suit a download-oriented workflow.

## 6.6 Packet switching

In packet switching, data is divided into smaller units called packets. Each packet carries addressing/control information and is forwarded through the network.

Two approaches:

### Datagram approach

Each packet is treated independently and may take a different route. Packets can arrive out of order or take different paths. The destination or higher-level protocol reassembles the data.

### Virtual-circuit approach

A logical path is established before data transfer. Packets follow the established logical route and carry information identifying the virtual circuit. The path is logical; it does not necessarily mean a dedicated physical wire.

## 6.7 IP addressing

An IP address identifies a network interface for communication using IP. IPv4 uses 32-bit addresses, commonly written in dotted-decimal form, such as `192.0.2.10`. IPv6 uses 128-bit addresses and hexadecimal notation.

An IP address has network and host/interface significance, interpreted with the prefix/subnet mask. Routers use destination IP information to forward packets between networks.

## 6.8 Remote login and remote access

Remote login allows a user to access a computer over a network. Older tools such as Telnet transmit data without modern encryption and should not be used across untrusted networks. SSH provides encrypted remote login and command execution.

Remote access can also mean connecting to an organisation's private network using a VPN.

## 6.9 SNMP

Simple Network Management Protocol (SNMP) is used to monitor and manage network devices.

Main components:
- **Manager / Network Management Station (NMS):** Collects information and manages devices.
- **Agent:** Software running on a managed device.
- **Managed device:** Router, switch, server or other network equipment.
- **MIB (Management Information Base):** Organised collection of managed objects/variables.
- **Messages/operations:** Queries, responses and notifications such as traps.

The manager can query an agent for information such as interface status or traffic counters. An agent can send a notification when an event occurs.

## PYQ connection

Questions include FTP and TFTP, TCP/IP, DNS components and Linux DNS configuration, POP3 and IMAP, packet switching, communication protocols, IP addressing, remote login, SNMP architecture and VPN. These appear across the 2022–2026 papers.

**Exam answer method:** Define the protocol/service, identify its layer or purpose, explain its working sequence, list important features, and compare it with a related protocol if asked. For DNS, FTP, TFTP, Kerberos and SNMP, a labelled flow diagram is particularly useful.

---

# 7. Priority 1 — Windows administration, domains and network services

Several papers specifically name Windows 2000, Windows NT or Windows XP. These are historical versions, so answer according to the version named in the question and the course material.

## 7.1 Workgroups and domains

### Workgroup

A workgroup is a peer-to-peer arrangement in which computers manage their own local user accounts and security. There is no central domain controller managing all accounts.

Suitable for small networks with limited central administration.

### Domain

A domain is a logical group of network resources managed centrally. User accounts, computers and security policies can be administered through domain services.

Advantages:
- Centralised user and computer management.
- Easier administration of permissions and policies.
- Central authentication.
- Better scalability for larger organisations.
- Easier access to shared network resources.

### Domain controller

A domain controller is a server that authenticates users and manages domain directory information and related services.

### Active Directory

Active Directory (AD), in Windows 2000, is Microsoft's directory service. It stores information about users, computers, groups and other network objects and supports centralised administration and authentication.

## 7.2 Local and domain user accounts

A **local user account** is created and stored on an individual computer. It is generally used to access that computer's local resources.

A **domain user account** is stored in the domain directory and can be used to authenticate to domain resources according to assigned permissions and policies.

### Groups

A group is a collection of user accounts. Instead of assigning the same permissions to each person individually, an administrator can assign permissions to a group and add users to it.

This simplifies administration and makes access control more consistent.

## 7.3 Trust relationships

A trust relationship allows one domain to accept authentication from another domain under defined rules.

In practical terms, a user authenticated in one trusted domain may be allowed to access resources in another domain, provided the resource permissions allow it.

A trust relationship does not automatically give every user access to every resource. Authentication and authorisation remain separate.

## 7.4 Kerberos in Windows domains

Windows 2000 Active Directory uses Kerberos as its principal network authentication protocol. The Kerberos flow is explained in the security section. In an exam answer, connect the KDC, authentication server, ticket-granting server, TGT and service ticket to the domain environment.

## 7.5 Windows user administration

Common tasks:
- Create a user account.
- Modify account properties.
- Reset a password.
- Disable or enable an account.
- Add/remove a user from groups.
- Set account restrictions and policies.
- Manage profiles and access rights.

A user profile stores a user's environment and settings. A roaming profile can make a user's settings available across multiple domain computers when configured by the administrator.

## 7.6 Windows registry

The Windows Registry is a hierarchical database that stores configuration settings for Windows, hardware, software, users and system components.

It is organised into keys and values. Important root keys include:
- `HKEY_LOCAL_MACHINE` (HKLM): machine-wide configuration.
- `HKEY_CURRENT_USER` (HKCU): settings for the current user.
- `HKEY_CLASSES_ROOT` (HKCR): file associations and COM-related information.
- `HKEY_USERS` (HKU): user profile information.
- `HKEY_CURRENT_CONFIG` (HKCC): current hardware profile information.

The exact registry layout varies by Windows version. Editing the registry incorrectly can cause application or system problems. Administrators should back up relevant settings and restrict access.

## 7.7 Windows file sharing and mapped drives

A mapped network drive assigns a drive letter to a shared folder on another computer or server.

For example, a shared folder such as `\\theircomputer\teamproject` can be mapped to `Z:`. A user can then access it through the drive letter.

A persistent mapping reconnects automatically; a non-persistent mapping requires the user to connect again. The December 2025 question specifically asks for a mapping that requires explicit logon each time, so the key concept is to avoid storing/reusing credentials and avoid automatic reconnection as appropriate to the Windows 2000 interface.

## 7.8 Windows network printing and print spooler

A print spooler manages print jobs between applications and printers.

Typical sequence:
1. A user sends a print request.
2. The operating system creates a print job.
3. The spooler stores the job in a queue.
4. The printer processes jobs as it becomes available.
5. The job is marked complete or reports an error.

Printer sharing makes a printer available to other network users. The administrator shares the printer, assigns an appropriate share name and sets permissions.

Common printer permissions in Windows environments include:
- Print: submit/manage one's own print jobs.
- Manage Documents: manage print jobs in the queue.
- Manage Printers: change printer properties and permissions.

Exact permission descriptions should be aligned to the Windows version and course text.

## 7.9 Windows services, FRS and distributed file systems

A Windows service is a background program that performs a system function without requiring a user to start it manually each time. Examples include networking, printing and directory-related services.

**File Replication Service (FRS)** in Windows 2000 was used to replicate files between servers, notably for SYSVOL content in Active Directory environments and configured replication sets. It helped keep copies of selected files consistent across servers.

A **distributed file system (DFS)** provides a unified logical view of shared folders that may physically reside on different servers. It makes network file resources easier to locate and manage.

## 7.10 Windows security features and hardening

Security measures include:
- User authentication and access control.
- File and folder permissions.
- Auditing.
- Group Policy.
- Encryption such as EFS.
- Security updates and service configuration.
- Disabling unnecessary services and accounts.
- Restricting remote access.
- Backups and recovery planning.

**Hardening** means reducing the system's attack surface by disabling unnecessary services, applying updates, enforcing strong configuration and limiting privileges.

## PYQ connection

Windows topics include domains, workgroups, trusts, local/domain accounts, groups, Kerberos, registry, auditing, security features, mapped drives, network printing, FRS, DFS, user profiles, Group Policy and Active Directory. They appear throughout the uploaded set, including the latest June 2026 paper.

**Answer method:** Identify the Windows feature, explain the problem it solves, describe its components or steps, and mention how it supports administration/security. When the question says Windows 2000, do not answer solely with modern Windows 10/11 menus or behaviour.

---

# 8. Priority 2 — Network devices, topologies and transmission media

## 8.1 Network topology

Topology describes how devices and links are arranged in a network. It can refer to physical layout or logical data flow.

### Bus topology

All devices connect to a common backbone cable. Data travels along the shared medium and devices examine whether a frame is addressed to them.

Advantages:
- Simple and inexpensive for small networks.
- Uses less cable than some layouts.

Disadvantages:
- A backbone failure can affect the entire network.
- Performance can decline as traffic increases.
- Fault location can be difficult.
- Terminators are required at the ends in traditional bus Ethernet.

### Star topology

Each device connects to a central hub or switch.

Advantages:
- Easy to add/remove devices.
- A single endpoint cable failure usually affects only that device.
- Easier fault isolation.

Disadvantages:
- Central device failure can affect the entire network.
- Requires more cable than a bus arrangement.

### Ring topology

Each device connects to two neighbouring devices, forming a ring. Data travels around the ring, often using a controlled access method such as token passing in classic implementations.

Advantages:
- Predictable access in token-based designs.
- Can avoid collisions in the classic token-passing model.

Disadvantages:
- A break or failed device can disrupt a simple ring unless bypass/redundancy is provided.
- Adding or removing devices can interrupt service in some designs.

### Mesh topology

Devices are connected through multiple paths. In a full mesh, every device has a direct connection to every other device.

Advantages:
- High redundancy.
- Multiple possible paths.
- Better resilience to individual link failures.

Disadvantages:
- Expensive cabling and ports.
- Complex installation and management.
- Full mesh becomes impractical as the number of devices grows.

For `n` devices, a full mesh has `n(n−1)/2` links.

### Tree topology

A hierarchical arrangement of star networks. It supports expansion and structured management, but failure of a high-level link or central device can affect a large branch.

### Hybrid topology

Combines two or more topology types, such as star-bus or star-ring.

## 8.2 Repeater, hub, bridge, switch, router and gateway

| Device | Main job | Typical OSI layer |
|---|---|---|
| Repeater | Regenerates/retimes a signal to extend a physical link | Physical (Layer 1) |
| Hub | Multiport repeater; repeats incoming bits to other ports | Physical (Layer 1) |
| Bridge | Connects LAN segments and filters frames using MAC addresses | Data Link (Layer 2) |
| Switch | Multiport bridge that forwards frames using MAC addresses | Mainly Data Link (Layer 2) |
| Router | Connects IP networks and forwards packets using network-layer addresses | Network (Layer 3) |
| Gateway | Connects systems/networks that may use different protocols or architectures; meaning depends on context | Can operate across layers |

### Repeater

A repeater receives a weakened or distorted signal, regenerates it and retransmits it. It does not understand IP addresses or make routing decisions. It operates at the physical layer.

### Bridge

A bridge connects LAN segments and learns which MAC addresses are reachable on which segment. It forwards or filters frames based on MAC addresses.

### Router

A router connects different IP networks. It examines network-layer addressing and uses a routing table to choose where to forward packets.

### Gateway

The word gateway is used broadly. A default gateway is usually the router a host uses to reach other networks. A protocol gateway can translate between different protocols or systems.

## 8.3 OSI reference model

The OSI model divides network communication into seven conceptual layers.

| Layer | Name | Main responsibility | Examples/idea |
|---:|---|---|---|
| 7 | Application | Network services for applications | HTTP, FTP, DNS |
| 6 | Presentation | Data representation, encoding, compression, encryption concepts | Format conversion |
| 5 | Session | Establishes, manages and ends communication sessions | Dialog control |
| 4 | Transport | End-to-end delivery, segmentation, reliability/flow control | TCP, UDP |
| 3 | Network | Logical addressing and routing | IP, routers |
| 2 | Data Link | Frames, MAC addressing, local-link delivery and error detection | Ethernet, switches |
| 1 | Physical | Transmission of raw bits over a medium | Cables, radio, repeaters |

Remember the order from bottom to top: Physical, Data Link, Network, Transport, Session, Presentation, Application.

## 8.4 Guided and unguided transmission media

**Guided media** carry signals through a physical path:
- Twisted-pair cable.
- Coaxial cable.
- Optical fibre.

**Unguided media** transmit electromagnetic signals through space:
- Radio waves.
- Microwaves.
- Infrared.
- Satellite communication.

### Optical fibre

Optical fibre carries information as pulses of light through a thin glass or plastic core. The light is guided through the fibre using the optical properties of the core and cladding.

Advantages:
- High bandwidth.
- Low signal loss over long distances.
- Not affected by ordinary electromagnetic interference in the same way as copper.
- Difficult to tap without detection compared with some copper links.

Disadvantages:
- Installation and repair require specialised skills.
- Fibre and optical equipment can be more expensive.
- Fragile compared with some copper cables.
- Requires optical transmitters and receivers.

## 8.5 Modem

A modem is a device that modulates and demodulates signals, allowing digital data to be carried over a communication medium whose signalling method differs from the computer's digital representation.

The term comes from **modulator-demodulator**.

Types often discussed in introductory courses:
- Dial-up modem.
- DSL modem.
- Cable modem.
- Wireless/cellular modem.
- Satellite modem.

Features can include data rate, supported standard, transmission medium, error correction, compression, interface and compatibility.

## 8.6 DTE and DCE

- **DTE (Data Terminal Equipment):** The endpoint that generates or consumes data, such as a computer or terminal.
- **DCE (Data Circuit-terminating Equipment / Data Communications Equipment):** Equipment that provides the communication interface to the transmission circuit, such as a modem in a traditional arrangement.

The exact terminology may vary slightly by context, but the key distinction is endpoint data equipment versus communication-circuit equipment.

## 8.7 LAN, MAN and WAN

| Network | Geographic scope | Example |
|---|---|---|
| LAN | Small area such as a room, building or campus | Office network |
| MAN | City or metropolitan area | City-wide institutional network |
| WAN | Large geographic area, countries or continents | Corporate inter-city network; the Internet is a global internetwork |

They differ in scale, ownership, technologies, costs and typical communication links.

## PYQ connection

The papers ask about repeater (June 2026), router vs bridge and OSI layers (June 2024), topologies including bus, ring and mesh (June 2022, December 2023, December 2024, June 2025, June 2026), guided/unguided media and optical fibre (December 2023, June 2025, June 2022), modems (December 2024 and December 2025), DTE/DCE (June 2022), and LAN/MAN/WAN (June 2023).

---

# 9. Priority 2 — Storage, file systems, RAID and fault tolerance

## 9.1 File systems

A file system controls how data is named, stored, organised and retrieved on a storage device. It keeps metadata about files, directories, permissions and storage allocation.

### FAT16 and FAT32

FAT stands for File Allocation Table. The file system uses a table to track how file data is stored across clusters.

- FAT16 uses a 16-bit allocation table entry format and supports fewer addressable clusters than FAT32.
- FAT32 uses a 32-bit entry format, with some bits reserved, and supports larger volumes/files than FAT16 in common implementations.

Both are relatively simple and widely compatible, but they lack many advanced security and reliability features associated with NTFS.

### NTFS

New Technology File System (NTFS) is a Windows file system with features such as:
- Access-control permissions.
- Journaling metadata support.
- Large-volume and large-file support.
- Compression.
- Disk quotas.
- Encryption support through EFS on supported Windows versions.

### EFS versus NTFS

NTFS is the file system. EFS is an encryption feature that can be used with NTFS. They are not competing file systems.

## 9.2 RAID

RAID means Redundant Array of Independent Disks. It combines multiple physical disks into a logical storage arrangement to improve performance, capacity, availability or a combination of these.

RAID does not replace backups. A RAID array can continue operating after certain disk failures, but it does not protect against accidental deletion, malware, theft, fire or all forms of corruption.

### Striping

Data is split into blocks and distributed across multiple disks. This can improve performance because disks work in parallel.

RAID 0 uses striping without redundancy. If one disk fails, the array's data is generally lost. RAID 0 provides performance/capacity benefits, not fault tolerance.

### Mirroring

The same data is written to two or more disks. If one disk fails, another copy may remain available.

### Parity

Parity information is calculated and stored so that lost data can be reconstructed after a supported disk failure.

### RAID levels 0 to 6

| RAID level | Basic method | Fault-tolerance summary |
|---|---|---|
| 0 | Striping, no redundancy | No disk-failure protection |
| 1 | Mirroring | Can survive a disk failure in a mirror pair; exact tolerance depends on layout |
| 2 | Bit-level striping with Hamming-code error correction | Uses multiple check disks; uncommon |
| 3 | Byte-level striping with dedicated parity disk | Can tolerate one disk failure |
| 4 | Block-level striping with dedicated parity disk | Can tolerate one disk failure; parity disk can be bottleneck |
| 5 | Block-level striping with distributed parity | Can tolerate one disk failure |
| 6 | Block-level striping with dual distributed parity | Can tolerate two disk failures |

The exact usable capacity depends on disk count and arrangement. RAID 2, 3 and 4 are mostly historical/less common in modern deployments, but the June 2026 question explicitly asks about RAID levels 0–6.

### Mirroring versus duplexing

- **Disk mirroring:** Data is duplicated on another disk. In a basic mirror, disks may share a controller.
- **Disk duplexing:** Data is mirrored but separate disk controllers are used, reducing the risk that a controller failure takes out both copies.

Both provide redundancy; duplexing adds controller-level redundancy.

## 9.3 Fault tolerance

A system is fault tolerant if it can continue to provide an acceptable level of service even when some component fails.

Techniques include:
- Redundant disks and RAID.
- Redundant power supplies.
- Multiple network paths.
- Failover servers.
- Replicated data.
- Error detection and correction.
- Regular backups and tested recovery plans.

**High availability** aims to minimise downtime. **Fault tolerance** aims to continue operating despite specified failures. They are related but not identical.

## 9.4 Backup and restoration

A backup is a separate copy of data used for recovery. Common strategies:
- Full backup: copies all selected data.
- Incremental backup: copies changes since the most recent backup of any type.
- Differential backup: copies changes since the last full backup.
- Off-site backup: stored at a separate location to protect against local disasters.

A backup is useful only if it can be restored. Restoration should be tested periodically.

## PYQ connection

RAID and striping occur in June 2022, June 2023 and June 2026. FAT/NTFS/EFS occur in June 2023, December 2023 and June 2025, with EFS also in December 2024. Fault tolerance appears in June 2024. Backup and restoration appear in June 2022 and June 2023.

---

# 10. Priority 2 — Memory, processes and CPU utilisation

## 10.1 Memory management

Memory management controls how RAM is allocated to processes and how the OS protects each process's address space.

Responsibilities:
- Track used and free memory.
- Allocate and release memory.
- Protect one process from another.
- Support virtual memory.
- Move or map data between RAM and secondary storage when needed.

## 10.2 Virtual memory

Virtual memory gives each process an address space that is separated from the actual physical RAM layout. The OS and hardware memory-management unit translate virtual addresses to physical memory locations.

Benefits:
- Programs can use an address space larger than the available physical RAM, subject to system limits and performance.
- Processes are isolated from one another.
- Memory can be allocated more flexibly.
- Shared memory and memory mapping are possible.

Virtual memory does not mean that disk storage is as fast as RAM. Excessive paging/swapping can make a system very slow.

## 10.3 Paging

Paging divides virtual memory into fixed-size pages and physical memory into frames. A page table maps virtual pages to physical frames.

If a needed page is not currently in RAM, a page fault occurs. The OS may load the page from secondary storage.

## 10.4 Page replacement

When RAM has no free frame and a required page must be loaded, the OS may need to choose a page to remove. A page-replacement algorithm makes this choice.

Common algorithms:
- FIFO: removes the page that has been in memory the longest.
- LRU: removes the page that has not been used for the longest time.
- Optimal: removes the page whose next use is farthest in the future; useful as a theoretical benchmark but requires future knowledge.

The December 2025 PYQ asks about the page-replacement algorithm used for managing memory in Linux. Be careful: the Linux kernel's real memory-management mechanisms are more complex than simply naming one textbook algorithm. If the question follows a specific prescribed text, use the algorithm and terminology taught there.

## 10.5 CPU scheduling

The CPU scheduler selects a ready process/thread to run.

Common scheduling algorithms:
- First Come First Served (FCFS).
- Shortest Job First (SJF).
- Priority scheduling.
- Round Robin.

Important measures:
- CPU utilisation.
- Throughput.
- Turnaround time.
- Waiting time.
- Response time.

Round Robin is common in time-sharing explanations because each ready process receives a time quantum.

## PYQ connection

Virtual memory and memory management appear in June 2025 and June 2024-related Linux memory material; page replacement appears in December 2025; process/thread management and multiprogramming appear in June 2022 and other sessions. Buffering and spooling questions also connect to CPU utilisation.

---

# 11. Priority 3 — GUI, X-Windows and human-computer interaction

## 11.1 Graphical User Interface (GUI)

A GUI lets users interact with a computer through graphical elements rather than only typed commands.

Common elements:
- Windows.
- Icons.
- Menus.
- Pointer.
- Buttons.
- Dialog boxes.
- Toolbars and controls.

Advantages:
- Easier for beginners to discover functions.
- Visual feedback.
- Supports direct manipulation.
- Reduces the need to memorise command syntax.

Limitations:
- Can use more memory and processing resources.
- Some advanced tasks may be faster through a command line.
- Poorly designed interfaces can confuse users.

## 11.2 GUI design principles

A good interface should:
- Be consistent in layout and terminology.
- Provide clear feedback after user actions.
- Prevent errors where possible.
- Use meaningful labels and familiar symbols.
- Keep the user's task and mental model in mind.
- Avoid unnecessary complexity.
- Provide appropriate help and recovery options.
- Make important controls visible and predictable.

Psychological considerations include attention, memory, perception, learning, user expectations and cognitive load. A user should not have to remember too many details between screens.

## 11.3 X-Windows / X Window System

The X Window System is a windowing system used mainly in Unix-like environments. It provides the foundation for graphical display, input and window management.

A key idea is its client-server architecture:
- **X server:** Manages the display, keyboard and pointer for a session.
- **X client:** An application that requests display/input services.
- **Window manager:** Controls window placement, borders, title bars and related behaviour. It is commonly a separate client, not the X server itself.

This can allow an application to run on one machine while displaying its interface on another, subject to network and security configuration.

## 11.4 Dialog boxes

A dialog box is a small window used to communicate with the user or collect information. Examples include open/save dialogs, confirmation boxes, warning messages and settings dialogs.

Good dialog design uses clear wording, meaningful defaults and an obvious way to confirm or cancel an action.

## 11.5 NeXT interface

The December 2025 paper asks about the NeXT computer and its user interface. Treat this as a historical GUI topic. Focus on the graphical desktop, windows, icons, menus and interaction style as described in your course material; do not confuse it with a general definition of modern macOS.

## PYQ connection

GUI functionality appears in June 2025 and December 2024. X-Windows appears in December 2023 and December 2024. GUI design psychology appears in December 2025; dialog boxes and NeXT interface also appear in that paper.

---

# 12. Priority 3 — Other Windows and Linux administration topics

## 12.1 Linux date and permissions

The `date` command displays the current system date/time. Setting the system clock normally requires administrator privileges or an authorised time-management capability. Ordinary users can generally display the date but cannot freely change the system clock.

## 12.2 Apache web server setup — conceptual view

Apache HTTP Server is web-server software. A typical Linux setup involves:
1. Install the Apache package using the distribution's package manager.
2. Start and enable the web-server service.
3. Place site files in the configured document root.
4. Configure virtual hosts if hosting multiple sites.
5. Check configuration syntax.
6. Allow HTTP/HTTPS traffic through the firewall.
7. Test locally and from another machine.
8. Review logs if the site does not work.

Package names, service names and configuration paths vary across distributions. The exam may expect a particular course-era Linux procedure.

## 12.3 Peer-to-peer networking

In a peer-to-peer network, computers can share resources directly without requiring a dedicated central server for every service. Each computer may act as both a client and a provider of resources.

Advantages:
- Simple and inexpensive for small networks.
- No dedicated server required.
- Easy to set up for limited sharing.

Disadvantages:
- Decentralised administration.
- User accounts and permissions may need to be managed separately.
- Harder to scale and audit.
- Backup and security can be inconsistent.

## 12.4 Windows Group Policy

Group Policy is used by administrators to configure user and computer settings centrally in a Windows domain. Policies can control security settings, desktop configuration, software behaviour and restrictions.

## 12.5 File Replication Service and Distributed File System

FRS replicates selected files between servers in Windows 2000 environments. DFS presents shared folders from different servers through a more unified namespace. Remember the distinction: replication copies/keeps data in sync; DFS helps users locate and access distributed shares.

---

# 13. Important comparison tables

These are useful for short-note and “differentiate between” questions.

## 13.1 Operating-system concepts

| Concept A | Concept B | Main difference |
|---|---|---|
| Multiprogramming | Multitasking | Multiprogramming keeps several jobs in memory to keep CPU busy; multitasking rapidly switches among tasks to support concurrent interactive work |
| Buffering | Spooling | Buffering temporarily holds data during transfer; spooling queues complete jobs for a device |
| Distributed OS | Network OS | Distributed OS aims to coordinate multiple machines as one integrated system; network OS provides services among visibly separate computers |
| Process | Thread | A process is an executing program with resources/address space; a thread is an execution path within a process |
| User mode | Kernel mode | Restricted application execution versus privileged OS execution |
| Hard real-time | Soft real-time | Missing a hard deadline is unacceptable; missing a soft deadline degrades quality |

## 13.2 Networking

| Concept A | Concept B | Main difference |
|---|---|---|
| TCP | UDP | TCP provides reliable ordered byte-stream delivery; UDP provides connectionless datagrams without delivery/order guarantees |
| FTP | TFTP | FTP is feature-rich and uses TCP; TFTP is simple and uses UDP |
| POP3 | IMAP | POP3 is download-oriented; IMAP synchronises mailbox state on the server |
| Bridge | Router | Bridge forwards frames using MAC addresses; router forwards packets using network-layer addresses |
| Repeater | Router | Repeater regenerates physical signals; router makes network-layer forwarding decisions |
| Guided media | Unguided media | Guided uses a physical path; unguided transmits through space |
| LAN | MAN | Local area versus metropolitan area |
| Datagram | Virtual circuit | Independent packet routing versus a pre-established logical path |
| Hub | Switch | Hub repeats bits to ports; switch forwards frames based on MAC learning |

## 13.3 Security

| Concept A | Concept B | Main difference |
|---|---|---|
| Authentication | Authorisation | Verifies identity versus determines permitted actions |
| Symmetric | Asymmetric cryptography | Shared secret key versus public/private key pair |
| Encryption | Hashing | Reversible with the key versus one-way digest operation |
| Firewall | IDS | Controls traffic according to policy versus detects suspicious activity and alerts |
| IDS | IPS | Detects/alerts versus can actively block/prevent |
| EFS | NTFS | File-encryption feature versus Windows file system |
| Mirroring | Duplexing | Duplicate data on disks versus mirrored disks with separate controllers |
| Backup | RAID | Separate recovery copy versus disk arrangement for performance/availability |

## 13.4 Storage

| RAID level | Technique | Disk failures tolerated |
|---|---|---:|
| RAID 0 | Striping | 0 |
| RAID 1 | Mirroring | Depends on mirror layout; typically one disk in a two-disk mirror |
| RAID 2 | Bit striping + Hamming-code ECC | Depends on exact arrangement |
| RAID 3 | Byte striping + dedicated parity | 1 |
| RAID 4 | Block striping + dedicated parity | 1 |
| RAID 5 | Block striping + distributed parity | 1 |
| RAID 6 | Block striping + dual distributed parity | 2 |

---

# 14. Diagrams to practise

You do not need to make every diagram artistic. Use a ruler, label the parts and make the direction of flow clear.

## 14.1 OS as an intermediary

```text
+-----------------------------+
|            Users            |
+-----------------------------+
              |
+-----------------------------+
|     Application Programs    |
+-----------------------------+
              |
+-----------------------------+
|       Operating System      |
| Process / Memory / Files /  |
| Devices / Security          |
+-----------------------------+
              |
+-----------------------------+
|          Hardware           |
| CPU / RAM / Disk / I/O       |
+-----------------------------+
```

## 14.2 DNS resolution

```text
User's computer
      |
      v
Recursive resolver
      |
      v
Root DNS server
      |
      v
TLD DNS server
      |
      v
Authoritative DNS server
      |
      v
IP address returned
```

## 14.3 Kerberos authentication

```text
Client --initial request--> Authentication Server
Client <--TGT-------------- Authentication Server

Client --TGT + service request--> Ticket-Granting Server
Client <--service ticket--------- Ticket-Granting Server

Client --service ticket---------> Application server
Client <-------service access---- Application server
```

## 14.4 OSI layers

```text
7  Application
6  Presentation
5  Session
4  Transport
3  Network
2  Data Link
1  Physical
```

## 14.5 Star and bus topologies

```text
STAR                         BUS

       PC1                  PC1   PC2   PC3
        |                    |     |     |
PC2 -- Switch -- PC3   ======+=====+=====+======
        |
       PC4                  Shared backbone
```

## 14.6 Packet-filtering firewall

```text
External network
       |
       v
+------------------+
|     Firewall     |
| Check IP/port/   |
| protocol/rules   |
+------------------+
       |
       v
Internal network
```

## 14.7 RAID 1 mirroring

```text
             Same data
                |
        +-------+-------+
        |               |
     Disk 1           Disk 2
     Copy A           Copy A
```

## 14.8 Process state model

```text
             admitted
   New -----------------> Ready
                            |
                         dispatch
                            v
                         Running
                         /     \
              I/O wait /       \ exit
                      v         v
                   Waiting   Terminated
                      |
              event completed
                      |
                      v
                    Ready
```

---

# 15. Rapid revision sheet

## Linux commands

- `pwd`: current directory.
- `ls -a`: include hidden entries.
- `ls -F`: append type indicators, including `/` for directories.
- `cat`: display/concatenate files.
- `head`: beginning of a file.
- `tail`: end of a file.
- `grep`: search matching lines.
- `wc`: count lines/words/bytes.
- `cmp`: byte-by-byte comparison.
- `diff`: line-based comparison.
- `chmod`: change permissions.
- `ps`: show processes.
- `kill`: send a signal to a process.
- `who`: show logged-in users.
- `man`: manual page.
- `fsck`: check/repair file system.
- `wall`: message all logged-in users.
- `write`: message one logged-in user.

## Linux permission values

- `r = 4`
- `w = 2`
- `x = 1`
- `755`: owner full; group and others read/execute.
- `644`: owner read/write; group and others read.
- `600`: owner read/write only.
- `400`: owner read only.

## OS concepts

- OS: manages hardware and provides services to programs.
- Multiprogramming: several programs in memory; CPU switches when one waits.
- Multitasking: rapid switching among tasks.
- Buffering: temporary data holding area.
- Spooling: queue of jobs for a device.
- Process: program in execution.
- Thread: execution unit within a process.
- System call: request for a kernel service.
- Virtual memory: virtual address space mapped to physical memory.
- Microkernel: small core with many services outside the kernel.
- Distributed OS: coordinates multiple computers as an integrated system.

## Security

- Confidentiality: prevent unauthorised disclosure.
- Integrity: prevent/detect unauthorised change.
- Availability: keep services accessible.
- Authentication: verify identity.
- Authorisation: determine permissions.
- Symmetric cryptography: shared secret key.
- Asymmetric cryptography: public/private key pair.
- Kerberos: ticket-based network authentication.
- Firewall: filters/controls traffic.
- VPN: protected logical connection over a shared network.
- IPSec: IP-layer security suite.
- EFS: Windows file encryption feature associated with NTFS.
- IDS: detects suspicious activity and alerts.
- Auditing: records events for accountability/investigation.

## Networking

- TCP: reliable, ordered transport.
- UDP: connectionless datagrams.
- IP: addressing and routing.
- DNS: resolves names to records.
- FTP: file transfer over TCP.
- TFTP: simple file transfer over UDP.
- POP3: download-oriented mail retrieval.
- IMAP: server-based mailbox synchronisation.
- SNMP: network monitoring/management.
- OSI: seven-layer reference model.
- Repeater: regenerates signals, Layer 1.
- Bridge/switch: forwards frames, Layer 2.
- Router: forwards IP packets, Layer 3.
- Modem: modulates/demodulates signals.

## Topology

- Bus: shared backbone.
- Star: central hub/switch.
- Ring: closed loop.
- Mesh: multiple paths.
- Tree: hierarchical structure.
- Hybrid: combination.

## Storage

- RAID 0: striping, no redundancy.
- RAID 1: mirroring.
- RAID 5: distributed parity, one-disk fault tolerance.
- RAID 6: dual parity, two-disk fault tolerance.
- Backup is not the same as RAID.
- NTFS is a file system; EFS is an encryption feature.

---

# 16. Seven-day study plan

This plan assumes you have limited time and need to prioritise. Adjust the hours to your actual availability; do not sacrifice all sleep trying to finish every line.

| Day | Main learning target | What to do |
|---|---|---|
| 1 | Linux commands, paths, permissions, filters and pipes | Learn command syntax; practise 15–20 command questions; explain permissions aloud |
| 2 | OS fundamentals, types, architecture, processes and system calls | Learn OS components, multiprogramming, multitasking, buffering, spooling, user/kernel modes and process states |
| 3 | Security foundations, cryptography, firewall and authentication | Learn CIA, threats, authentication factors, symmetric/asymmetric encryption, firewall types and limitations |
| 4 | Kerberos, VPN, IPSec, EFS, auditing, IDS and risk analysis | Draw Kerberos and VPN/security diagrams; practise 5- and 10-mark frameworks |
| 5 | Networking protocols and services | Cover TCP/IP, DNS, FTP/TFTP, POP3/IMAP, packet switching, IP addressing and SNMP |
| 6 | Windows administration, topology, devices, media, RAID and file systems | Cover domains, trusts, users, registry, printing, RAID, OSI, topologies, modems and transmission media |
| 7 | Full revision and timed PYQ practice | Attempt selected questions without notes; revise weak topics, definitions, diagrams and comparisons |

## Daily study cycle

For each major topic:
1. **Understand:** Read the explanation and examples.
2. **Recall:** Close the notes and explain the topic without looking.
3. **Write:** Attempt one PYQ in your own words.
4. **Check:** Compare your answer against the topic headings and correct missing points.
5. **Review:** Revisit the topic briefly the next day.

## If time becomes very tight

Do not abandon the whole plan. Prioritise:
1. Linux command syntax and permissions.
2. OS fundamentals: multiprogramming, multitasking, buffering, spooling, processes, system calls and user/kernel mode.
3. Security: CIA, cryptography, firewall, Kerberos, VPN and authentication.
4. Networking: DNS, TCP/IP, FTP/TFTP, OSI, topology and network devices.
5. Windows domains/users/trust and RAID/file systems.

Then use remaining time for GUI, modem, SNMP, FRS, DFS, Group Policy and other short notes.

---

# 17. PYQ coverage checklist

Use this checklist to test whether you have covered the major question families in the uploaded papers.

## Linux
- [ ] Basic commands and command output
- [ ] Hidden files and directory indicators
- [ ] `head`, `tail`, `grep`, `wc`, `cmp`, `diff`
- [ ] `ps`, `kill`, `who`, `pwd`, `date`, `man`
- [ ] File and directory structure
- [ ] Absolute and relative paths
- [ ] Read/write/execute permissions
- [ ] `chmod` and permission numbers
- [ ] Redirection
- [ ] Filters and pipelines
- [ ] Device files
- [ ] `fsck`
- [ ] Linux user and system administration
- [ ] Backup and restoration
- [ ] Shell scripting basics
- [ ] Apache setup concept

## Operating systems
- [ ] Definition, goals, components and functions
- [ ] Batch, multiprogramming, multitasking and real-time OS
- [ ] Distributed OS vs network OS
- [ ] Buffering and spooling
- [ ] System calls
- [ ] Process and thread management
- [ ] User mode and kernel mode
- [ ] Virtual memory and page replacement
- [ ] Microkernel and layered architecture
- [ ] THE operating system

## Security
- [ ] CIA triad and security goals
- [ ] Security breaches and classifications
- [ ] Authentication methods
- [ ] Symmetric and asymmetric cryptography
- [ ] Digital signatures and certificates
- [ ] Kerberos
- [ ] Firewall types, working and limitations
- [ ] VPN and VPN technologies
- [ ] IPSec
- [ ] EFS
- [ ] Auditing
- [ ] Intrusion detection
- [ ] Security risk analysis
- [ ] System access control
- [ ] Backup and off-site retention

## Networking
- [ ] Communication protocols
- [ ] TCP/IP
- [ ] FTP and TFTP
- [ ] DNS components, goals and resolution
- [ ] DNS configuration concept in Linux
- [ ] POP3 and IMAP
- [ ] Packet switching: datagram and virtual circuit
- [ ] IP addressing
- [ ] Remote login
- [ ] SNMP architecture
- [ ] OSI layers
- [ ] Network topologies
- [ ] LAN, MAN and WAN
- [ ] Repeater, bridge, router and gateway
- [ ] Modem and types
- [ ] DTE and DCE
- [ ] Guided/unguided media and optical fibre

## Windows
- [ ] Workgroups and domains
- [ ] Local and domain accounts
- [ ] User groups
- [ ] Trust relationships
- [ ] Kerberos in Windows domains
- [ ] Registry
- [ ] User profiles
- [ ] Group Policy
- [ ] Active Directory
- [ ] Auditing and security features
- [ ] Mapped drives
- [ ] Network printing and print permissions
- [ ] FRS and DFS
- [ ] Hardening services

## Storage and interface topics
- [ ] FAT16 and FAT32
- [ ] NTFS and EFS
- [ ] RAID 0–6
- [ ] Striping, mirroring and duplexing
- [ ] Fault tolerance
- [ ] Backup strategies
- [ ] GUI and dialog boxes
- [ ] GUI design principles
- [ ] X Window System
- [ ] NeXT interface

---

## Final advice

You do not need to reproduce a textbook word for word. For most descriptive questions, a strong answer has this structure:

1. **Definition:** State what the concept is.
2. **Purpose:** Explain why it is needed.
3. **Working:** Explain the process in logical steps.
4. **Components/types:** Explain the important parts.
5. **Example/diagram:** Add one where it genuinely helps.
6. **Advantages/limitations:** Include these when relevant.
7. **Conclusion:** Summarise the significance.

For a 5-mark question, be selective and direct. For a 10-mark question, explain the mechanism and components in more depth. Use the exact terminology in the question and answer every part of it.

**The goal is not to predict the paper perfectly. The goal is to understand the recurring concepts well enough that a new wording does not throw you off.**
