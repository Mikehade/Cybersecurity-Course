# Cybersecurity Learning Journey

## A Structured 6–12 Month Roadmap for a Complete Beginner

### Purpose

This roadmap is designed for someone who wants to **break into cybersecurity from a beginner level** and needs a structured path rather than a collection of random videos.

The philosophy is:

> **Understand computers → learn to program → master Linux and the command line → understand networking → learn security fundamentals → practice in legal labs → specialize → build a portfolio.**

The goal is not to turn someone into a “hacker” as quickly as possible.

The goal is to build someone who understands **how computers, operating systems, networks, applications and security controls actually work**.

That foundation makes everything that comes afterward much easier.

---

# 1\. The Overall Roadmap

```
                         CYBERSECURITY
                              │
                              ▼
                 ┌────────────────────────┐
                 │  PHASE 0               │
                 │  Computer Foundations  │
                 └────────────┬───────────┘
                              │
                              ▼
                 ┌────────────────────────┐
                 │  PHASE 1               │
                 │  Linux + Bash           │
                 └────────────┬───────────┘
                              │
                    ┌─────────┴─────────┐
                    ▼                   ▼
          ┌─────────────────┐   ┌─────────────────┐
          │  Python         │   │  Networking     │
          │  CS50P          │   │  TCP/IP, DNS... │
          └────────┬────────┘   └────────┬────────┘
                   │                     │
                   └──────────┬──────────┘
                              ▼
                 ┌────────────────────────┐
                 │  PHASE 3               │
                 │  Security Fundamentals │
                 │  CS50 Cybersecurity    │
                 │  Security+             │
                 └────────────┬───────────┘
                              │
                              ▼
                 ┌────────────────────────┐
                 │  PHASE 4               │
                 │  Hands-on Cyber Labs   │
                 │  TryHackMe             │
                 │  OverTheWire           │
                 └────────────┬───────────┘
                              │
                              ▼
                 ┌────────────────────────┐
                 │  PHASE 5               │
                 │  Practical Security    │
                 │  TCM / Tools / CTFs     │
                 └────────────┬───────────┘
                              │
                              ▼
                    ┌─────────┴─────────┐
                    ▼                   ▼
             RED TEAM / WEB       BLUE TEAM / DFIR
             Pentesting           SOC / Detection
                    │                   │
                    ▼                   ▼
                 Portfolio + GitHub + Projects
                              │
                              ▼
                       JOB / INTERNSHIP
```

---

# 2\. The Most Important Rule

Do **not** measure progress by:

> “How many courses have I watched?”

Measure progress by:

> “What can I actually do without following a tutorial?”

Every phase therefore has a **checkpoint**.

If the learner cannot complete the checkpoint, they should not simply move on because they finished the videos.

---

# 3\. Phase 0 — Computer Foundations

### Estimated time

**2–4 weeks**

### Objective

Before cybersecurity, understand what a computer actually is.

The learner should understand:

- CPU
- RAM
- Storage
- Operating systems
- Files and directories
- Processes
- Programs
- Applications
- Users and permissions
- Basic virtualization
- What happens when a program runs
- Basic command-line concepts

---

## Primary Course: CS50x

[Harvard CS50p 2026 — Introduction to Computer Science with Python](<https://www.edx.org/learn/python/harvard-university-cs50-s-introduction-to-programming-with-python>)

CS50x is not strictly a cybersecurity course. That is precisely why it is useful.

It teaches computational thinking, algorithms, data structures, memory, programming and how computers work underneath the software. The current 2026 syllabus includes C, algorithms, memory, data structures, Python, SQL, web programming and more.  edX

### Recommended approach

Do **not** feel obligated to complete every CS50x component before continuing.

For a cybersecurity learner, particularly valuable sections are:

- Week 0 — Computational thinking
- Week 1 — C
- Week 2 — Arrays
- Week 3 — Algorithms
- Week 4 — Memory
- Week 5 — Data Structures
- Week 6 — Python
- Week 7 — SQL

The C/memory portions are particularly useful because cybersecurity eventually requires understanding what happens beneath high-level languages.

### Checkpoint

The learner should be able to explain:

> What is a process?

> What is memory?

> What is a file?

> What is an operating system?

> What is the difference between an application and a process?

> What happens when I execute a program?

If they cannot explain these concepts, slow down.

---

# 4\. Phase 1 — Linux Fundamentals

### Estimated time

**3–5 weeks**

Linux is extremely important in cybersecurity.

The learner should become comfortable living in a terminal.

Do not start with Kali Linux and immediately start running hacking tools.

First learn **Linux itself**.

---

## Primary Resource: TryHackMe Pre Security

[TryHackMe — Pre Security](<https://tryhackme.com/path/outline/beginner?utm_source=chatgpt.com>)

TryHackMe's current Pre Security path is specifically designed for people starting from zero. It covers computer fundamentals, operating systems, software, networking, the web and basic attacks/defenses.  TryHackMe+1

This is an excellent companion to CS50.

---

## Linux Topics

Learn:

- Linux filesystem
- `/`
- `/home`
- `/etc`
- `/var`
- `/tmp`
- `/usr`
- `/bin`
- `/sbin`
- Relative vs absolute paths
- `pwd`
- `ls`
- `cd`
- `mkdir`
- `touch`
- `cp`
- `mv`
- `rm`
- `cat`
- `less`
- `head`
- `tail`
- `grep`
- `find`
- `which`
- `man`
- pipes
- redirection
- environment variables
- processes
- permissions
- users
- groups
- `sudo`
- SSH
- package management

---

# 5\. Phase 2 — Bash Scripting

### Estimated time

**2–4 weeks**

This is where your original idea is especially good.

I would absolutely include Bash.

The learner should not merely know how to type Linux commands.

They should learn to **automate them**.

Bash is both a command interpreter and a programming language, and shell scripts are simply files containing commands that Bash executes.  GNU+1

---

## Primary Resource
[Bash Scripting Playlist](<https://www.youtube.com/playlist?list=PLT98CRl2KxKGj-VKtApD8-zCqSaN2mD4w>)

[GNU Bash Reference Manual](<https://www.gnu.org/software/bash/manual/?utm_source=chatgpt.com>)

Use the manual as a reference rather than trying to read it cover-to-cover.

---

## Bash Topics

Learn:

- Variables
- Arguments
- `$1`, `$2`, `$@`
- Exit codes
- `if`
- `for`
- `while`
- Functions
- Command substitution
- Pipes
- Redirection
- `grep`
- `awk`
- `sed`
- `cut`
- `sort`
- `uniq`
- `xargs`
- `chmod`
- `cron`
- Environment variables
- Basic error handling

---

## Bash Projects

Do not finish Bash without writing scripts.

### Project 1 — System information script

Display:

- hostname
- username
- operating system
- kernel
- IP address
- disk usage
- memory usage
- running processes

### Project 2 — Log analyzer

Given a log file:

- count lines
- identify repeated IP addresses
- identify failed login attempts
- produce a summary

### Project 3 — File integrity checker

Create a script that:

1. Calculates hashes of selected files.
2. Saves the baseline.
3. Runs again later.
4. Detects changed files.

### Project 4 — Backup script

Automatically:

- select a directory
- compress it
- timestamp the backup
- store it in a backup directory
- report success/failure

### Bash checkpoint

The learner should be able to sit at a Linux terminal and automate a repetitive task without copying a tutorial.

---

# 6\. Phase 3 — Python

### Estimated time

**6–10 weeks**

Python is one of the most useful programming languages for cybersecurity.

But the objective is not:

> “Learn Python because hackers use Python.”

The objective is:

> **Learn programming well enough to automate, analyze and build security tools.**

---

## Primary Course: CS50P

[CS50's Introduction to Programming with Python](<https://cs50.harvard.edu/python/?utm_source=chatgpt.com>)

This is one of the strongest choices in the entire roadmap.

The current course covers:

- Functions
- Variables
- Conditionals
- Loops
- Exceptions
- Unit testing
- Libraries
- File I/O
- Regular expressions
- Classes
- Objects
- Debugging

and includes problem sets and a final project.  edX+1

### Important

Do the **problem sets**.

Do not treat CS50P as a Netflix series.

The recommended workflow is:

```
Watch lecture
      ↓
Understand concepts
      ↓
Do exercises
      ↓
Attempt problem set yourself
      ↓
Debug
      ↓
Complete problem set
      ↓
Move forward
```

---

# 7\. Python for Cybersecurity

After the basic CS50P material, begin applying Python to security-related problems.

Learn:

- `os`
- `sys`
- `subprocess`
- `pathlib`
- `json`
- `csv`
- `re`
- `hashlib`
- `socket`
- `requests`
- basic HTTP
- APIs
- logging
- argument parsing
- virtual environments
- exception handling
- testing

---

## Python Projects

### Project 1 — Password generator

Create a configurable password generator.

### Project 2 — Hash calculator

Given a file:

- calculate SHA-256
- display the hash
- optionally compare it with a known hash

### Project 3 — Log analyzer

Parse authentication logs and report:

- failed logins
- successful logins
- repeated IP addresses
- timestamps

### Project 4 — File integrity monitor

Create a Python version of the Bash integrity checker.

### Project 5 — HTTP information tool

Given a URL in a controlled environment:

- make an HTTP request
- display status code
- display selected headers
- measure response time

### Project 6 — Security automation toolkit

Eventually combine several utilities into one command-line program.

---

# 8\. Git and GitHub

### Introduce this early — not at the end.

Cybersecurity learners should maintain their work from the beginning.

Learn:

- `git init`
- `git clone`
- `git add`
- `git commit`
- `git status`
- `git log`
- branches
- merging
- `.gitignore`
- README files

---

## Resource

[Pro Git — Official Git Book](<https://git-scm.com/book/en/v2?utm_source=chatgpt.com>)

The Pro Git book is freely available and covers Git from getting started through branching and more advanced concepts.  Git

---

# 9\. Phase 4 — Networking

### Estimated time

**6–8 weeks**

This is one of the most important phases.

A cybersecurity professional who does not understand networking is severely limited.

Learn:

### Networking fundamentals

- LAN
- WAN
- IP addresses
- MAC addresses
- IPv4
- IPv6
- Subnetting
- CIDR
- Default gateway
- DHCP
- DNS
- NAT
- ARP
- ICMP

### Protocols

- Ethernet
- TCP
- UDP
- IP
- DNS
- DHCP
- HTTP
- HTTPS
- SSH
- FTP
- SMTP
- IMAP
- TLS

### Network concepts

- Ports
- Sockets
- Client/server
- Routing
- Firewalls
- Proxies
- VPNs
- Packet capture
- Network segmentation

---

# 10\. Hands-on Networking

Use:

[TryHackMe Pre Security](<https://tryhackme.com/path/outline/beginner?utm_source=chatgpt.com>)

and later:

[TryHackMe Cyber Security 101](<https://tryhackme.com/path/outline/cybersecurity101?utm_source=chatgpt.com>)

The current Cyber Security 101 path includes networking, Linux, Windows/Active Directory, command line, cryptography, offensive security and defensive security.  TryHackMe

---

# 11\. Wireshark

Introduce packet analysis after the networking fundamentals.

[Wireshark Documentation](<https://www.wireshark.org/docs/?utm_source=chatgpt.com>)

Learn to:

- capture packets
- identify TCP handshakes
- identify DNS queries
- inspect HTTP
- follow TCP streams
- understand source/destination
- filter traffic
- recognize suspicious traffic patterns

The objective is not to memorize Wireshark filters.

The objective is:

> **Look at network traffic and understand what is happening.**

---

# 12\. Nmap

Once networking fundamentals are solid:

[Nmap — Official Project Guide](<https://nmap.org/book/?utm_source=chatgpt.com>)

Nmap is a network discovery and security auditing tool. Its official guide starts with basic host discovery and port scanning and progresses into more advanced functionality.  Nmap+1

Learn:

- hosts
- ports
- services
- TCP/UDP
- service discovery
- version detection
- basic enumeration

### Important

Only scan:

- systems you own
- your own lab
- explicitly authorized systems
- platforms designed for security training

---

# 13\. Phase 5 — Cybersecurity Fundamentals

### Estimated time

**4–6 weeks**

Now the learner has enough technical foundation to understand cybersecurity properly.

This is where I would add **two complementary resources**.

---

# 14\. CS50's Introduction to Cybersecurity

[CS50's Introduction to Cybersecurity — Harvard](<https://cs50.harvard.edu/cybersecurity/?utm_source=chatgpt.com>)

This is a particularly good addition because it preserves the **CS50 teaching style** that motivated this roadmap.

It is designed for technical and non-technical audiences and covers securing:

- accounts
- data
- systems
- software
- privacy

The course currently consists of five weeks plus a final project.  edX+1

This should be treated as a **conceptual cybersecurity course**, not a replacement for hands-on labs.

---

# 15\. Professor Messer — Security+ SY0-701

### Estimated time

**6–10 weeks**

[Professor Messer — Security+ SY0-701 Training Course](<https://www.professormesser.com/security-plus/sy0-701/sy0-701-video/sy0-701-comptia-security-plus-course/?utm_source=chatgpt.com>)

This becomes the structured cybersecurity textbook.

The current course contains **121 videos and approximately 15 hours of video**, organized around the SY0-701 objectives.  Professor Messer

Study it systematically.

Topics include:

- General security concepts
- Threats
- Vulnerabilities
- Security architecture
- Secure design
- Identity and access management
- Cryptography
- Security operations
- Incident response
- Risk management
- Governance
- Compliance

Professor Messer's current SY0-701 resources remain actively maintained in 2026.  Professor Messer+1

### Important

Do not study Security+ purely for memorization.

For every concept ask:

> “What does this look like on an actual computer or network?”

For example:

**Professor Messer:** DNS security

↓

**Lab:** Inspect DNS traffic in Wireshark

↓

**Python:** Parse DNS-related data

↓

**Security:** Understand why DNS matters to defenders

That is how theory becomes skill.

---

# 16\. Phase 6 — Hands-on Cybersecurity

### Estimated time

**6–10 weeks**

This is where the learner transitions from:

> “I understand cybersecurity.”

to:

> “I can actually do cybersecurity.”

---

# 17\. TryHackMe Cyber Security 101

[TryHackMe Cyber Security 101](<https://tryhackme.com/path/outline/cybersecurity101?utm_source=chatgpt.com>)

This should be one of the main practical foundations.

The current path covers:

- Linux
- Windows
- Active Directory
- command line
- networking
- cryptography
- offensive security
- defensive security
- security careers

and is explicitly designed as a beginner-friendly foundation.  TryHackMe+1

### Recommended rule

Don't rush through rooms.

For every lab:

1. Read the objective.
2. Attempt it yourself.
3. Research when stuck.
4. Complete the task.
5. Write down what you learned.
6. Reproduce it later without the walkthrough.

---

# 18\. OverTheWire Bandit

[OverTheWire Bandit](<https://overthewire.org/wargames/bandit/?utm_source=chatgpt.com>)

Bandit is specifically aimed at absolute beginners and teaches foundational command-line skills through progressively harder levels.  OverTheWire

Use it alongside Linux/Bash.

It is particularly useful for developing:

- command-line confidence
- SSH familiarity
- file manipulation
- permissions
- searching
- pipelines
- problem-solving

---

# 19\. Phase 7 — Practical Ethical Hacking

Only after the foundation is established.

### Resource

[TCM Security](<https://tcm-sec.com/?utm_source=chatgpt.com>)

Look for:

**Practical Ethical Hacking**

The learner should now be ready to understand topics such as:

- reconnaissance
- enumeration
- vulnerability identification
- exploitation concepts
- privilege escalation
- web security
- Active Directory
- penetration-testing methodology

The important difference is that they now understand **why the tools work**, rather than merely copying commands.

---

# 20\. The Learner's Security Laboratory

At this point, create a dedicated lab.

A basic setup might contain:

```
                    HOST COMPUTER
                         │
                 ┌───────┴───────┐
                 │ Virtualization │
                 └───────┬───────┘
                         │
        ┌────────────────┼────────────────┐
        │                │                │
        ▼                ▼                ▼
     Linux VM        Windows VM      Security VM
                                  (e.g. Kali)
        │                │                │
        └────────────────┴────────────────┘
                         │
                    Isolated Lab
```

The important principle is **isolation**.

The learner should practice attacks only against:

- their own virtual machines
- intentionally vulnerable machines
- CTF environments
- TryHackMe
- Hack The Box
- PortSwigger labs
- other explicitly authorized environments

---

# 21\. Web Security

Once the learner understands:

- Linux
- Python
- networking
- HTTP
- basic security
- command line

begin web security.

---

## PortSwigger Web Security Academy

[PortSwigger Web Security Academy](<https://portswigger.net/web-security?utm_source=chatgpt.com>)

This is one of the resources I would strongly recommend adding to the original roadmap.

It is free and contains interactive labs covering areas including:

- SQL injection
- XSS
- CSRF
- XXE
- API testing
- authentication
- access control
- SSRF
- web cache issues
- NoSQL injection
- web LLM attacks

The Academy is continuously updated and specifically designed for safe, legal web-security practice.  PortSwigger

### Recommended progression

```
HTTP
 ↓
Cookies
 ↓
Sessions
 ↓
Authentication
 ↓
Authorization
 ↓
SQL
 ↓
SQL Injection
 ↓
XSS
 ↓
CSRF
 ↓
SSRF
 ↓
Access Control
 ↓
API Security
```

---

# 22\. Phase 8 — Problem Solving

### John Hammond

[John Hammond on YouTube](<https://www.youtube.com/@_JohnHammond?utm_source=chatgpt.com>)

Do not use this as the primary beginner course.

Use John Hammond after the fundamentals.

Watch how he approaches:

- CTFs
- malware
- vulnerabilities
- security investigations
- challenge environments

The objective is to develop **security problem-solving ability**.

A good rule:

> Attempt the challenge first. Watch the walkthrough second.

---

# 23\. Phase 9 — Choose a Specialization

Do not specialize too early.

The learner should first get enough exposure to different areas to discover what they enjoy.

After the foundation, choose one primary direction.

---

# 24\. Path A — Red Team / Penetration Testing

Best for someone who enjoys:

- breaking things
- finding vulnerabilities
- Linux
- networking
- web applications
- problem-solving

### Roadmap

```
Networking
   ↓
Linux
   ↓
Python/Bash
   ↓
Security Fundamentals
   ↓
TryHackMe
   ↓
Nmap
   ↓
Burp Suite
   ↓
Web Security Academy
   ↓
TCM Practical Ethical Hacking
   ↓
CTFs
   ↓
Active Directory
   ↓
Jr Penetration Tester pathway
   ↓
Portfolio
```

TryHackMe's current roadmap has a dedicated **Jr Penetration Tester** path following the foundation stage.  TryHackMe

---

# 25\. Path B — Blue Team / SOC

Best for someone who enjoys:

- investigation
- logs
- monitoring
- incident response
- detection
- understanding attacks from the defender's perspective

### Roadmap

```
Networking
   ↓
Linux
   ↓
Windows
   ↓
Security Fundamentals
   ↓
Security+
   ↓
TryHackMe Cyber Security 101
   ↓
SOC Level 1
   ↓
SIEM
   ↓
Detection
   ↓
Incident Response
   ↓
DFIR
```

TryHackMe currently provides dedicated SOC Level 1 and SOC Level 2 paths for this direction.  TryHackMe

---

# 26\. Path C — Digital Forensics / DFIR

For someone who becomes interested in investigating what happened after an incident:

### Learn

- Windows internals
- filesystems
- event logs
- memory
- disk artifacts
- timelines
- evidence
- incident response
- malware investigation

### Resource

[13Cubed](<https://www.youtube.com/@13Cubed?utm_source=chatgpt.com>)

Use 13Cubed **after** the learner has a strong Windows/Linux/security foundation.

---

# 27\. Path D — Web Application Security

For someone who loves programming and websites:

```
Python
   ↓
HTML
   ↓
JavaScript basics
   ↓
HTTP
   ↓
SQL
   ↓
Authentication
   ↓
Web security
   ↓
Burp Suite
   ↓
PortSwigger Academy
   ↓
Bug bounty / web pentesting
```

The PortSwigger Academy should be one of the primary resources here.  PortSwigger

---

# 28\. Path E — Cloud Security

After the core foundation:

```
Networking
      ↓
Linux
      ↓
Python
      ↓
Security Fundamentals
      ↓
AWS/Azure Fundamentals
      ↓
IAM
      ↓
Cloud Networking
      ↓
Logging
      ↓
Containers
      ↓
Cloud Security
```

Do not jump into cloud security before understanding networking and IAM.

---

# 29\. The Five YouTube Channels

The original list is good, but I would use the channels differently.

### 1\. NetworkChuck

Use for:

- Linux
- networking
- command line
- general infrastructure

[NetworkChuck on YouTube](<https://www.youtube.com/@NetworkChuck?utm_source=chatgpt.com>)

**Role:** supplementary explanation.

Do not attempt to watch everything.

---

### 2\. Professor Messer

Use for:

- Security+
- systematic security fundamentals

[Professor Messer](<https://www.professormesser.com/?utm_source=chatgpt.com>)

**Role:** structured security curriculum.

---

### 3\. TCM Security

Use for:

- practical ethical hacking
- penetration testing
- offensive security

[TCM Security](<https://tcm-sec.com/?utm_source=chatgpt.com>)

**Role:** practical offensive-security training.

---

### 4\. John Hammond

Use for:

- CTFs
- malware
- investigations
- practical problem-solving

[John Hammond on YouTube](<https://www.youtube.com/@_JohnHammond?utm_source=chatgpt.com>)

**Role:** develop the ability to think through security problems.

---

### 5\. 13Cubed

Use for:

- DFIR
- digital forensics
- Windows investigation

[13Cubed on YouTube](<https://www.youtube.com/@13Cubed?utm_source=chatgpt.com>)

**Role:** specialization resource for blue team/DFIR.

---

# 30\. How the Resources Fit Together

This is the most important part.

Do **not** think:

> NetworkChuck → Professor Messer → TCM → John Hammond.

Think:

```
                 COMPUTER SCIENCE
                     CS50x
                       │
                       ▼
               LINUX + COMMAND LINE
          TryHackMe + Bash + Bandit
                       │
             ┌─────────┴─────────┐
             ▼                   ▼
          PYTHON              NETWORKING
          CS50P            TryHackMe/Networking
             │                   │
             └─────────┬─────────┘
                       ▼
             CYBERSECURITY THEORY
              CS50 Cybersecurity
                       │
                       ▼
                 SECURITY+
              Professor Messer
                       │
                       ▼
               HANDS-ON LABS
                 TryHackMe
                       │
                       ▼
              PRACTICAL SECURITY
               TCM / Nmap / etc.
                       │
                       ▼
               WEB / CTF / SOC
                       │
                       ▼
                 SPECIALIZATION
```

This is much better than trying to complete five unrelated YouTube playlists.

---

# 31\. Suggested 12-Month Schedule

## Months 1–2 — Computer + Linux

### Study

- CS50x
- TryHackMe Pre Security
- Linux fundamentals
- Bash basics
- OverTheWire Bandit

### Build

- Linux notes
- Bash scripts
- system-information script
- backup script

### Outcome

The learner is comfortable using a Linux terminal.

---

# Months 3–4 — Python

### Study

- CS50P
- Python exercises
- Git/GitHub

### Build

- password generator
- hash calculator
- log analyzer
- file-integrity checker
- HTTP information tool

### Outcome

The learner can write Python without following a tutorial line-by-line.

---

# Months 4–5 — Networking

### Study

- TCP/IP
- DNS
- HTTP/HTTPS
- subnetting
- ports
- routing
- DHCP
- NAT
- Wireshark

### Practice

- capture traffic
- analyze DNS
- analyze TCP handshakes
- inspect HTTP
- learn Nmap in authorized labs

### Outcome

The learner can look at a network diagram or packet capture and understand what is happening.

---

# Months 5–6 — Security Fundamentals

### Study

- CS50 Cybersecurity
- Professor Messer Security+ SY0-701

### Learn

- CIA triad
- authentication
- authorization
- cryptography
- hashing
- PKI
- vulnerabilities
- threats
- risk
- security architecture
- incident response
- security controls
- IAM

### Outcome

The learner understands cybersecurity vocabulary and concepts rather than merely memorizing terms.

---

# Months 6–8 — Hands-on Security

### Main platform

TryHackMe Cyber Security 101.

Supplement with:

- OverTheWire
- Wireshark
- Nmap
- Linux labs
- Windows labs

### Outcome

The learner can perform basic security tasks inside authorized environments.

---

# Months 8–10 — Practical Security

Choose:

### Offensive

- TCM
- TryHackMe Jr Penetration Tester
- PortSwigger Academy
- CTFs

OR

### Defensive

- TryHackMe SOC Level 1
- SIEM
- detection
- incident response
- Windows investigation
- 13Cubed

---

# Months 10–12 — Portfolio + Specialization

Stop collecting courses.

Start producing evidence of ability.

Build:

### Project 1

**Python Security Toolkit**

### Project 2

**Bash System Administration Toolkit**

### Project 3

**Network Analysis Report**

Use an authorized lab capture.

### Project 4

**Incident Investigation**

Document a simulated security incident.

### Project 5

**Web Security Assessment**

Use a PortSwigger lab or deliberately vulnerable application.

Document:

- vulnerability
- impact
- evidence
- reproduction in the lab
- remediation

---

# 32\. The GitHub Portfolio

Create a GitHub repository structure such as:

```
cybersecurity-journey/
│
├── linux/
│   ├── commands.md
│   ├── permissions.md
│   └── troubleshooting.md
│
├── bash/
│   ├── system-info.sh
│   ├── backup.sh
│   └── log-analyzer.sh
│
├── python/
│   ├── hash-tool/
│   ├── log-analyzer/
│   ├── integrity-monitor/
│   └── http-tool/
│
├── networking/
│   ├── tcp-ip.md
│   ├── dns.md
│   ├── subnetting.md
│   └── wireshark/
│
├── security/
│   ├── security-plus-notes/
│   ├── incident-response/
│   └── threat-models/
│
├── web-security/
│   └── portswigger-labs/
│
└── README.md
```

The README should eventually tell the story:

> I started with no cybersecurity background.

> I learned Linux, Bash, Python and networking.

> I learned security fundamentals.

> I built these projects.

> I completed these labs.

> I specialized in X.

That is much more valuable than a GitHub repository containing 50 copied scripts.

---

# 33\. Weekly Study Structure

A good schedule is **10–15 hours per week**.

For example:

| Day | Activity |
| --- | --- |
| Monday | Course/lecture |
| Tuesday | Course + exercises |
| Wednesday | Linux/Bash/Python practice |
| Thursday | Networking/security |
| Friday | Lab |
| Saturday | Project/CTF |
| Sunday | Review + documentation |

The critical component is **Saturday/project time**.

That is where passive knowledge becomes skill.

---

# 34\. The 40/40/20 Rule

For every 10 hours of study:

### 4 hours — Learn

Videos, lectures, books.

### 4 hours — Practice

Labs, exercises, commands, coding.

### 2 hours — Build

Projects and documentation.

Do not allow the journey to become:

```
YouTube
YouTube
YouTube
YouTube
YouTube
```

Instead:

```
Learn
 ↓
Practice
 ↓
Break something in a lab
 ↓
Fix it
 ↓
Document it
 ↓
Build something
```

---

# 35\. What NOT to Do

Avoid these common beginner traps.

### ❌ Don't start with Kali Linux

Kali is a toolbox.

It is not cybersecurity knowledge.

### ❌ Don't memorize hacking commands

Understand what the command is doing.

### ❌ Don't spend six months watching videos

Hands-on work should begin very early.

### ❌ Don't collect certifications

Skills first.

Certifications can support the skills later.

### ❌ Don't jump between 30 YouTube channels

Use one primary resource per subject.

### ❌ Don't copy CTF walkthroughs

Attempt the challenge first.

### ❌ Don't scan random websites

Use authorized environments.

### ❌ Don't make “hacking Instagram/Facebook/Wi-Fi” the goal

The goal is to understand security professionally.

---

# 36\. Recommended Primary Resource per Skill

| Skill | Primary Resource |
| --- | --- |
| Computer Science | CS50x |
| Python | CS50P |
| Linux | TryHackMe Pre Security |
| Bash | GNU Bash + practice |
| Command Line | OverTheWire Bandit |
| Git | Pro Git |
| Networking | TryHackMe + practical labs |
| Cybersecurity fundamentals | CS50 Cybersecurity |
| Security fundamentals | Professor Messer SY0-701 |
| Hands-on cybersecurity | TryHackMe Cyber Security 101 |
| Network analysis | Wireshark |
| Network discovery | Nmap |
| Ethical hacking | TCM Security |
| Web security | PortSwigger Academy |
| CTF/problem solving | John Hammond |
| DFIR | 13Cubed |
| Blue Team | TryHackMe SOC Level 1 |
| Red Team | TryHackMe Jr Penetration Tester |

---

# 37\. The Minimum Core Curriculum

If the learner becomes overwhelmed, **do not abandon the roadmap**.

Reduce it to this:

```
1. CS50x
       ↓
2. Linux
       ↓
3. Bash
       ↓
4. CS50P
       ↓
5. Networking
       ↓
6. CS50 Cybersecurity
       ↓
7. Professor Messer Security+
       ↓
8. TryHackMe
       ↓
9. TCM / PortSwigger
       ↓
10. Specialization
```

Everything else is supplementary.

---

# 38\. The Finish Line

The learner does **not** need to know everything before applying for an entry-level opportunity.

A reasonable first target is:

### Foundation

- Linux
- Windows basics
- Bash
- Python
- Git

### Networking

- TCP/IP
- DNS
- HTTP
- ports
- subnetting
- Wireshark

### Security

- authentication
- authorization
- encryption
- hashing
- vulnerabilities
- risk
- incident response
- security controls

### Practical

- TryHackMe
- Nmap
- Wireshark
- Burp Suite
- basic enumeration
- basic security analysis

### Professional

- GitHub
- documentation
- technical writing
- communication
- portfolio
- legal/ethical understanding

At that point, the learner is no longer merely **“someone interested in cybersecurity.”**

They have the beginnings of a technical cybersecurity skillset.

---

# 39\. Final Recommended Journey

If I were personally mentoring this person from zero, I would give them this exact sequence:

```
                    START
                      │
                      ▼
                CS50x 2026
                      │
                      ▼
            TryHackMe Pre Security
                      │
                      ▼
              Linux Fundamentals
                      │
                      ▼
                 Bash Scripting
                      │
                      ▼
              OverTheWire Bandit
                      │
              ┌───────┴────────┐
              ▼                ▼
          CS50P Python      Networking
              │                │
              └───────┬────────┘
                      ▼
             Git + GitHub
                      │
                      ▼
          CS50 Cybersecurity
                      │
                      ▼
       Professor Messer Security+
                      │
                      ▼
       TryHackMe Cyber Security 101
                      │
                      ▼
          Nmap + Wireshark + HTTP
                      │
                      ▼
             ┌────────┴────────┐
             ▼                 ▼
        TCM Security      PortSwigger
             │                 │
             └────────┬────────┘
                      ▼
              CTF / Real Labs
                      │
                      ▼
              CHOOSE SPECIALTY
                 /          \
                /            \
               ▼              ▼
          RED TEAM         BLUE TEAM
          Pentesting       SOC / DFIR
               │              │
               ▼              ▼
          Portfolio        Portfolio
               │              │
               └──────┬───────┘
                      ▼
              Internship / Job
```

## The philosophy behind the roadmap

The learner should progressively move through four stages:

**Stage 1 — “I don't understand computers.”**

↓

**Stage 2 — “I understand computers and can program.”**

↓

**Stage 3 — “I understand how computers communicate and how they can be secured.”**

↓

**Stage 4 — “I can investigate, defend, test or build things in a controlled environment.”**

That is the journey I would aim for.

The biggest improvement over the original plan is that **NetworkChuck, Professor Messer, TCM, John Hammond and 13Cubed are no longer the curriculum themselves**. They are supporting resources inside a larger progression.

The backbone is:

**CS50 → Linux/Bash → Python → Networking → CS50 Cybersecurity → Security+ → TryHackMe → practical specialization.**

That gives the learner a much more coherent “CS50/Professor Leonard-style” journey while still getting them into hands-on cybersecurity relatively early.

I would use this as the **master document** for the learner. The next useful step would be turning it into a **week-by-week 52-week syllabus**, with each week specifying _exactly what to watch, what to read, what lab to complete, what to code, and what project/checkpoint to submit_.
