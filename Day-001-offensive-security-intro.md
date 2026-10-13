# Day 001 — Cybersecurity Learning Log

**Date:** October 13, 2026  
**Learning Path:** TryHackMe Pre-Security  
**Room:** Offensive Security Intro

## Learning Objectives
- Understand the basics of offensive security.
- Practise web content discovery in an authorized training lab.
- Learn basic HTTP status codes.
- Understand the difference between discovering a page and identifying a vulnerability.
- Review authentication and authorization.

## Practical Work

### 1. Web Content Discovery with DIRB

Command used in the TryHackMe lab:

`dirb http://fakebank.thm`

**Observed paths:**
- `/bank-transfer`
- `/images`

The command discovered paths in the simulated lab. Finding a path does not automatically mean that a vulnerability exists.

### 2. HTTP Status Codes

- **200 OK:** The request was successful.
- **301 Moved Permanently:** The resource has permanently moved to another URL.

Status codes help interpret HTTP responses, but they do not independently determine whether a website is secure.

### 3. Simulated FakeBank Exercise

Completed the exercise in TryHackMe's simulated FakeBank environment and observed the lab success message.

This was a training exercise in an authorized environment, not a test against a real banking system.

## Key Concepts Learned
- Offensive security
- Reconnaissance and enumeration
- Directory discovery
- HTTP status codes
- Hidden pages and access control
- Authentication versus authorization

## Evidence and Completion

- Room completion: 4/4 tasks and 32 points — screenshot reviewed.
- DIRB command and discovered paths — screenshot reviewed.
- FakeBank lab result — screenshot reviewed.
- Revision quiz: 3/3 correct answers reported by me; separate screenshot evidence was not identified.

## Reflection

I learned that discovering a web path is different from proving a security vulnerability. I also reviewed how authentication verifies identity while authorization determines permitted actions.

## Next Steps
- Continue the existing Pre-Security learning path in sequence.
- Review the concepts through further practice.
- Maintain accurate, sanitized documentation of future labs.

**Evidence integrity:** This report describes activity in an authorized training lab. It does not claim professional experience or independent mastery.

**Publication status:** Published on GitHub; public accessibility verified on October 13, 2026.
