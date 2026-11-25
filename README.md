# Task 1 - Cybersecurity Fundamentals

Hi! This repository contains my notes and basic understanding from Task 1 of the VirtualWorks Ethical Hacking Internship.

---

## 1. What is Cybersecurity & Ethical Hacking?

**Cybersecurity** is basically protecting computers, networks, phones, and personal data from hackers or unauthorized access.

**Ethical Hacking** means testing a system for security weaknesses *with proper permission* from the owner. Instead of stealing data or breaking things, ethical hackers find bugs so the company can fix them before real attackers find them.

* **Main Difference:** It comes down to **permission**. Ethical hackers have written approval to test a system, whereas malicious hackers break in illegally.
* **Example:** A company hires a security tester to check if their login page can be bypassed. The tester finds a weak password rule and tells the company how to fix it.

---

## 2. Types of Hackers

From the video, hackers are mainly divided into three types based on why they hack and whether they have permission:

* **White Hat Hackers:** These are the ethical hackers. They have permission to test systems and help improve security (like bug bounty hunters).
* **Black Hat Hackers:** These are malicious hackers who break into systems illegally to steal data, demand money, or cause damage.
* **Grey Hat Hackers:** They sit somewhere in between. They don't have permission to test a system, so what they do is technically illegal, even if they aren't trying to steal anything.
  * *Example:* Someone finds a security flaw on a public website without asking first, and then messages the website owner to warn them about it.

---

## 3. The CIA Triad

The **CIA Triad** is a core model in cybersecurity that stands for three main goals when protecting any data or system:

1. **Confidentiality (Keeping data private)**
   * Making sure only the right people can see sensitive information.
   * *Example:* Using passwords, OTPs/2FA, and encryption so strangers can't read your private chats or bank details.

2. **Integrity (Keeping data accurate)**
   * Making sure data isn't changed, edited, or tampered with by someone who shouldn't have access.
   * *Example:* When you download a file, checking its hash value to be sure nobody modified the file or added a virus to it.

3. **Availability (Keeping systems running)**
   * Making sure websites, apps, and data are accessible whenever users actually need them.
   * *Example:* A college portal having backup servers so students can still check their exam results even if one server crashes.

---

## 4. Common Threats & How They Affect Systems

* **Malware (Malicious Software):**
  * Any harmful software built to damage a device, spy on users, or steal files (like viruses, trojans, and spyware).
  * **Impact:** Slows down the PC, corrupts files, or quietly steals saved passwords in the background.
  * *Example:* Downloading a free cracked game from a random site that secretly installs a keylogger on your laptop.

* **Phishing:**
  * Tricking people into giving away sensitive details (like passwords or card numbers) by pretending to be a trusted brand via fake emails, SMS, or lookalike websites.
  * **Impact:** Attackers get into your accounts using your own login details and can spread further inside a network.
  * *Example:* Getting a fake email saying "Your bank account will be blocked today, click here to verify" that takes you to a fake login page.

* **Ransomware:**
  * A type of malware that locks or encrypts all the files on a computer so you can't open them, and demands money (ransom) to unlock them.
  * **Impact:** Completely stops work because nobody can access important files or databases (directly hits **Availability**).
  * *Example:* An office PC gets infected through an email attachment, and every document on the shared drive gets locked with a pop-up asking for payment to restore access.
