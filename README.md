# Cybersecurity and Python Learning for noobs

a plan to learn cybersec and python for total noobs. can take 6 months (Python+HTB) or 12 months (Python only). Or, mix and match content from months to suit you.

Total cost: ~$210 upfront, $30 monthly. Only cost is a Lenovo laptop and a Linux USB to install Fedora/Ubuntu. Everything else is totally free.

# Sites

- https://libgen.is/ - for all textbooks, free books, etc
- https://hackthebox.com/ - for learning pentesting
- https://book.hacktricks.xyz/ - how to hack specific services
- https://www.codecademy.com/ - learning to code

# Tools

- Fedora for programming (OS): https://fedoraproject.org/workstation/download
- ParrotOS for hacking (OS): https://www.parrotsec.org/download/
- 256GB SSD, 8GB RAM ThinkPad for ~$200: https://www.ebay.com/b/Lenovo-ThinkPad-PC-Laptops-Netbooks/177/bn_7115838996
- python editor: https://www.jetbrains.com/pycharm/
- code editor: https://code.visualstudio.com/
- network scanner: https://nmap.org/
  - https://github.com/RustScan/RustScan
- ChatGPT for $20/mo: https://chat.openai.com/
  - Useful to ask questions. i.e. "How can I run a port scan on this host?" or "Why is this Python function declared like this?"
- GitHub Copilot for $10/mo: https://github.com/features/copilot
  - Same use as ChatGPT. Experiment with both and see what you like. Bonus of this is that it gets IDE integrations, and ChatGPT does not.

# Discord

For asking for help and learning with others.

- HTB: https://discord.com/invite/hackthebox
- Python: https://discord.com/invite/python

# Other links

- https://help.hackthebox.com/en/articles/8117054-guided-mode-for-machines
- https://www.youtube.com/watch?v=jQ194vU4Qkk

# Material

## Python

- "Python Crash Course" by Eric Matthes
- "Automate the Boring Stuff with Python" by Al Sweigart
- "Python for Kids: A Playful Introduction to Programming" by Jason R. Briggs
- "Invent Your Own Computer Games with Python" by Al Sweigart
- "Head-First Python: A Brain-Friendly Guide" by Paul Barry

## Cybersec

- "Black Hat Python: Python Programming for Hackers and Pentesters" by Justin Seitz
- "Violent Python: A Cookbook for Hackers, Forensic Analysts, Penetration Testers, and Security Engineers" by TJ O'Connor
- "Python for Cybersecurity: Using Python for Cyber Offense and Defense" by Howard E. Poston III
- "Gray Hat Python: Python Programming for Hackers and Reverse Engineers" by Justin Seitz
- "Practical Python Programming for IoT, AI, and Cybersecurity" by Sunil Cheruvu, Anil Kumar, Ned Smith, and David Wheeler

# Python Course outline

This is a year-long Python programming course. It does not cover Hackthebox labs.

## Quarter 1: Introduction to Python Programming

Books: "Python Crash Course" by Eric Matthes & "Automate the Boring Stuff with Python" by Al Sweigart

### Week 1-4: Basics of Python

    Python Crash Course: Part I (Chapters 1-5)
    Chapter 1: Installing Python
    Chapter 2: Variables and Simple Data Types
    Chapter 3: Introducing Lists
    Chapter 4: Working with Lists
    Chapter 5: If Statements
    
### Week 5-8: Working with Functions and Classes

    Python Crash Course: Part I (Chapters 6-9)
    Chapter 6: Dictionaries
    Chapter 7: User Input and while Loops
    Chapter 8: Functions
    Chapter 9: Classes
    
### Week 9-12: Automating Tasks

    Automate the Boring Stuff with Python (Chapters 1-6)
    Chapter 1: Python Basics
    Chapter 2: Flow Control
    Chapter 3: Functions
    Chapter 4: Lists
    Chapter 5: Dictionaries and Structuring Data
    Chapter 6: Manipulating Strings

    
## Quarter 2: Intermediate Python Projects
Books: "Python Crash Course" by Eric Matthes & "Invent Your Own Computer Games with Python" by Al Sweigart

### Week 13-16: Web Development Basics

    Python Crash Course: Part II (Chapters 18-19)
    Chapter 18: Getting Started with Django
    Chapter 19: User Accounts
    
### Week 17-20: Game Development

    Invent Your Own Computer Games with Python (Chapters 1-8)
    Chapter 1: The Interactive Shell
    Chapter 2: Writing Programs
    Chapter 3: Guess the Number
    Chapter 4: Jokes
    Chapter 5: Dragon Realm
    Chapter 6: Hangman
    Chapter 7: Tic Tac Toe
    Chapter 8: Reversi

### Week 21-24: Automating More Complex Tasks

    Automate the Boring Stuff with Python (Chapters 7-9)
    Chapter 7: Pattern Matching with Regular Expressions
    Chapter 8: Input Validation
    Chapter 9: Reading and Writing Files

## Quarter 3: Introduction to Cybersecurity

Books: "Black Hat Python" by Justin Seitz & "Violent Python" by TJ O'Connor

### Week 25-28: Introduction to Cybersecurity Concepts

    Black Hat Python (Chapters 1-3)
    Chapter 1: Setting Up Your Python Environment
    Chapter 2: Network Sockets
    Chapter 3: Using Python to Execute System Commands

### Week 29-32: Offensive Security

    Black Hat Python (Chapters 4-7)
    Chapter 4: Network Scanner
    Chapter 5: Sniffers, Man-in-the-Middle and Attacks
    Chapter 6: Web Hacking
    Chapter 7: Extending Burp Suite
    
### Week 33-36: Practical Cybersecurity Projects

    Violent Python (Chapters 1-4)
    Chapter 1: The Shell and Automating Tasks
    Chapter 2: Social Engineering
    Chapter 3: Network Traffic Analysis
    Chapter 4: Wireless Pentesting

## Quarter 4: Advanced Cybersecurity and Final Projects

Books: "Gray Hat Python" by Justin Seitz & "Python for Cybersecurity" by Howard E. Poston III

### Week 37-40: Reverse Engineering and Debugging

    Gray Hat Python (Chapters 1-4)
    Chapter 1: Introduction to Reverse Engineering
    Chapter 2: Debuggers
    Chapter 3: Building a Basic Debugger
    Chapter 4: Hooking Windows APIs

### Week 41-44: Advanced Offensive and Defensive Techniques

    Python for Cybersecurity (Chapters 1-4)
    Chapter 1: Python for Offensive Security
    Chapter 2: Python for Defensive Security
    Chapter 3: Malware Analysis
    Chapter 4: Network Defense

### Week 45-48: IoT and AI in Cybersecurity

    Practical Python Programming for IoT, AI, and Cybersecurity (Chapters 1-3)
    Chapter 1: Introduction to IoT and Cybersecurity
    Chapter 2: AI in Cybersecurity
    Chapter 3: Practical Projects in IoT Security

### Week 49-52: Capstone Project and Review

Work on a comprehensive capstone project integrating Python programming and cybersecurity concepts.
Review key topics and prepare a presentation or report on the project.

Capstone ideas:

- Network Security Suite: A tool to scan networks, detect common flaws, try to exploit them, monitor traffic, and generate reports
- Web Application Security Testing Framework: A tool to crawl webpages, identify exploits, scan for SQLi and XSS, automatically exploit potential vulnerabilities, and provide remediation advice
- IoT Security Analysis and Defense System: A tool to discover IoT devices, to scan specific protocols like MQTT and CoAP, and a defense system like a firewall and intrusion detection system for IoT networks.

# 6-Month Course Outline: Python Programming and Cybersecurity with Hack The Box

This is a 6-month accelerated course plan. It covers both Python programming and hackthebox.

## Month 1: Foundations of Python and Cybersecurity
Books: "Python Crash Course" by Eric Matthes & "Black Hat Python" by Justin Seitz

### Week 1-2: Basics of Python

    Python Crash Course: Part I (Chapters 1-5)
    Chapter 1: Installing Python
    Chapter 2: Variables and Simple Data Types
    Chapter 3: Introducing Lists
    Chapter 4: Working with Lists
    Chapter 5: If Statements
    
### Week 3-4: Introduction to Cybersecurity Concepts

    Black Hat Python (Chapters 1-3)
    Chapter 1: Setting Up Your Python Environment
    Chapter 2: Network Sockets
    Chapter 3: Using Python to Execute System Commands
    
    Hack The Box Labs:
    Complete HTB Starting Point labs to get familiar with the platform and basic penetration testing concepts.

## Month 2: Intermediate Python and Network Security

Books: "Automate the Boring Stuff with Python" by Al Sweigart & "Violent Python" by TJ O'Connor

### Week 5-6: Automating Tasks

    Automate the Boring Stuff with Python (Chapters 1-6)
    Chapter 1: Python Basics
    Chapter 2: Flow Control
    Chapter 3: Functions
    Chapter 4: Lists
    Chapter 5: Dictionaries and Structuring Data
    Chapter 6: Manipulating Strings
    
### Week 7-8: Offensive Security Basics

    Violent Python (Chapters 1-2)
    Chapter 1: The Shell and Automating Tasks
    Chapter 2: Social Engineering
    
    Hack The Box Labs:
    Focus on easy-level HTB machines to practice enumeration and basic exploitation techniques.
    
## Month 3: Advanced Python Projects and Web Security
Books: "Python Crash Course" by Eric Matthes & "Black Hat Python" by Justin Seitz

### Week 9-10: Web Development Basics

    Python Crash Course: Part II (Chapters 18-19)
    Chapter 18: Getting Started with Django
    Chapter 19: User Accounts
    
### Week 11-12: Web Application Security

    Black Hat Python (Chapters 6-7)
    Chapter 6: Web Hacking
    Chapter 7: Extending Burp Suite
    
    Hack The Box Labs:
    Target web application machines and challenges on HTB to apply web security concepts.
    
## Month 4: Pentesting and Malware Analysis
Books: "Gray Hat Python" by Justin Seitz & "Violent Python" by TJ O'Connor

### Week 13-14: Intermediate Pentesting Techniques

    Gray Hat Python (Chapters 1-2)
    Chapter 1: Introduction to Reverse Engineering
    Chapter 2: Debuggers

### Week 15-16: Malware Analysis

    Violent Python (Chapters 3-4)
    Chapter 3: Network Traffic Analysis
    Chapter 4: Wireless Pentesting

    Hack The Box Labs:
    Work on intermediate HTB machines focusing on network and wireless security challenges.
    
## Month 5: Defensive Security and Advanced Topics

Books: "Python for Cybersecurity" by Howard E. Poston III & "Practical Python Programming for IoT, AI, and Cybersecurity" by Sunil Cheruvu et al.

### Week 17-18: Defensive Security

    Python for Cybersecurity (Chapters 1-2)
    Chapter 1: Python for Offensive Security
    Chapter 2: Python for Defensive Security

### Week 19-20: IoT and AI in Cybersecurity

    Practical Python Programming for IoT, AI, and Cybersecurity (Chapters 1-2)
    Chapter 1: Introduction to IoT and Cybersecurity
    Chapter 2: AI in Cybersecurity
    
    Hack The Box Labs:
    Work on more advanced HTB machines, focusing on defensive techniques and IoT-related challenges.

## Month 6: Capstone Project and Advanced HTB Labs

Books: Combination of learned materials and Hack The Box practice

### Week 21-22: Capstone Project Planning

Define the scope and objectives of the capstone project.
Begin initial research and planning.

### Week 23-24: Capstone Project Implementation

Work on the capstone project, integrating Python programming and cybersecurity skills.
Document the process and findings.

### Week 25-26: Advanced Hack The Box Labs

Attempt some of the hardest HTB machines and challenges.
Focus on areas of interest or weaknesses identified during the course.

### Week 27-28: Review and Presentation

Finalize the capstone project.
Prepare a presentation or report on the capstone project.
Review key concepts and skills learned throughout the course.

Capstone ideas:
- Automated Penetration Testing Toolkit: A toolkit that automates various pentest tasks, from recon to exploits, using Python. Recon tools to gather info about targets, a vulnerability scanner to identify vulnerabilities, exploit scripts to test identified vulnerabilities, and post-exploitation tools to maintain access and gather further data
- Cybersecurity Incident Response System: Create a system to manage and respond to cybersecurity incidents, including detection, analysis, and remediation. Create an incident detection module using log analysis and anomaly detection. Create an incident analysis tool to investigate and understand the nature of the threat. Create automated remediation scripts to contain and eliminate the threat. Create a reporting tool to document incidents.
- Web Application Firewall (WAF) with Machine Learning: Build a web application firewall that uses machine learning to detect and block malicious traffic. Create a traffic monitoring module to capture and analyze web traffic. Use a machine learning model to identify patterns indicative of attacks. Create a blocking mechanism to prevent malicious requests from reaching the web application. Create a reporting tool to provide insights into blocked attacks and overall security posture.



# Project-based learning course outlines

TBD.