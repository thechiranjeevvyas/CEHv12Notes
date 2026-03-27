# Section 02: Hacking Methodology

## CEH Hacking Methodology

The CEH hacking methodology consists of the following phases:

- Gaining access
  - Cracking passwords
  - Vulnerability exploitation
- Escalating privileges
- Maintaining access
  - Executing applications
  - Hiding files
- Covering tracks
  - Clearing logs

### Exploit

> An exploit (from the English verb to exploit, meaning "to use something to one’s own advantage") is a piece of software, a chunk of data, or a sequence of commands that takes advantage of a bug or vulnerability to cause unintended or unanticipated behavior to occur on computer software, hardware, or something electronic (usually computerized).

- [https://en.wikipedia.org/wiki/Exploit\_(computer_security)](<https://en.wikipedia.org/wiki/Exploit_(computer_security)>)
  Footprinting

[Definition](../definitions/definitions_F.md#footprinting)

### Password cracking

In cryptanalysis and computer security, password cracking is the process of recovering passwords from data that has been stored in or transmitted by a computer system in scrambled form.
A common approach (brute-force attack) is to repeatedly try guesses for the password and to check them against an available cryptographic hash of the password.

Links

- [https://en.wikipedia.org/wiki/Password_cracking](https://en.wikipedia.org/wiki/Password_cracking)

## Privilege Escalation

> Privilege escalation is the act of exploiting a bug, a design flaw, or a configuration oversight in an operating system or software application to gain elevated access to resources that are normally protected from an application or user.

Links

- [https://en.wikipedia.org/wiki/Privilege_escalation](https://en.wikipedia.org/wiki/Privilege_escalation)

## Vulnerability Assesment

> A vulnerability assessment is the process of identifying, quantifying, and prioritizing (or ranking) the vulnerabilities in a system.
> Examples of systems for which vulnerability assessments are performed include, but are not limited to, information technology systems, energy supply systems, water supply systems, transportation systems, and communication systems.

Links

- [https://en.wikipedia.org/wiki/Vulnerability_assessment](https://en.wikipedia.org/wiki/Vulnerability_assessment)

## Cyber Kill Chain

> Developed by Lockheed Martin, the Cyber Kill Chain® framework is part of the Intelligence Driven Defense® model for identification and prevention of cyber intrusions activity.
> The model identifies what the adversaries must complete in order to achieve their objective.
> The chain:

- Reconnaissance
  - Harvesting email addresses, conference information, etc.
- Weaponization
  - Coupling exploit with backdoor into deliverable payload
- Delivery
  - Delivering weaponized bundle to the victim via email, web, USB, etc.
- Exploitation
  - Exploiting a vulnerability to execute code on victim's system
- Installation
  - Installing malware on the asset
- Command and control (C2)
  - Command channel for remote manipulation of victim
- Action on objectives
  - Intruders accomplish their goals

Links

- [https://www.lockheedmartin.com/en-us/capabilities/cyber/cyber-kill-chain.html](https://www.lockheedmartin.com/en-us/capabilities/cyber/cyber-kill-chain.html)

## Tactics, Techniques and Procedures

> Tactics, Techniques, and Procedures (TTPs) is an essential concept in terrorism and cyber security studies.
> The role of TTPs in terrorism analysis is to identify individual patterns of behavior of a particular terrorist activity, or a particular terrorist organisation, and to examine and categorize more general tactics and weapons used by a particular terrorist activity, or a particular terrorist organisation.

Links

- [https://en.wikipedia.org/wiki/Terrorist_Tactics,\_Techniques,\_and_Procedures](https://en.wikipedia.org/wiki/Terrorist_Tactics,_Techniques,_and_Procedures)

## Indicator of Compromise

Indicator of compromise (IoC) in computer forensics is an artifact observed on a network or in an operating system that, with high confidence, indicates a computer intrusion.
Typical IoCs are virus signatures and IP addresses, MD5 hashes of malware files, or URLs or domain names of botnet command and control servers.
After IoCs have been identified via a process of incident response and computer forensics, they can be used for early detection of future attack attempts using intrusion detection systems and antivirus software.

Links

- [https://en.wikipedia.org/wiki/Indicator_of_compromise](https://en.wikipedia.org/wiki/Indicator_of_compromise)

## MITRE ATT&CK Framework

MITRE ATT&CK® is a globally-accessible knowledge base of adversary tactics and techniques based on real-world observations.
The ATT&CK knowledge base is used as a foundation for the development of specific threat models and methodologies in the private sector, in government, and in the cybersecurity product and service community.

Links

- [https://attack.mitre.org/](https://attack.mitre.org/)

## Diamond Model of Intrusion Analysis

The diamond model of intrusion analysis is a model used by information security professionals to authenticate and track cyber threats.
