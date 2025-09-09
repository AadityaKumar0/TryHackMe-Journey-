# Offensive Security Intro (TryHackMe Room)

**Category:** Offensive Security  
**Difficulty:** Easy  
**Date Completed:** 09/09/2025  

---

## 🎯 Objectives
- Understand what offensive security means.  
- Learn the mindset of a hacker: "To outsmart a hacker, you need to think like one."  
- Practice hacking a website in a safe, legal lab environment.  
- Use tools like `dirb` to discover hidden functionality in web applications.  

---

## 🛠️ Tools & Commands Used
- **Terminal** → to execute text-based commands.  
- **dirb** → brute-force tool for finding hidden website pages.  
  ```bash
  dirb http://fakebank.thm

# Methodology & Notes

### Offensive Security Basics
"To outsmart a hacker, you need to think like one."  
This is the core of Offensive Security. It involves breaking into computer systems, exploiting software bugs, and finding loopholes in applications to gain unauthorized access.  
The goal is to understand hacker tactics and enhance our system defenses.  

- Offensive Security = simulating hacker actions to find vulnerabilities.  
- Defensive Security = protecting systems from attacks.  

---

### Beginning the Learning Journey
- In this room, I was guided through hacking my first website in a **legal and safe environment**.  
- The labs can be reverted to their initial state, so experimentation is encouraged.  

---

### Briefing: FakeBank Scenario
- Objective: Hack the **FakeBank** application to simulate stealing money.  
- Given: A normal user account in the system.  
- Approach: Find hidden functionality (secret URLs) that expose sensitive features not meant for regular users.  

---

### Using `dirb` to Find Hidden Pages
1. Opened the **Terminal** on the lab machine.  
2. Ran the command:  
   ```bash
   dirb http://fakebank.thm

## 🔗 Room Link
[Offensive Security Intro – TryHackMe](https://tryhackme.com/room/offensivesecurityintro)

