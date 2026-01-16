# 🔐 How I Passed TCM Security’s Practical Junior Penetration Tester Certification

## TL;DR

- PJPT is a hands-on, practical exam that tests internal network pentesting skills.  
- Focus on Active Directory and practice the enumerate -> attack -> re-enumerate loop.  
- Build a strong evidence-driven report with clear screenshots and remediation.  
- Practice in lab environments and keep a steady study cadence.

---

## Hello everyone

It’s been a while since I passed this exam, but I wanted to give back to anyone interested in the certification and help guide them on their journey. Hope this helps.

Getting dropped into a two day lab environment can feel like being thrown in the deep end. Here’s how to swim. I passed the PJPT as my first cybersecurity certification, and I learned some hard-won lessons I wish I’d known upfront. Let’s dive in.

---

## Overview

The Practical Junior Penetration Tester (PJPT) certification tests your ability to perform an internal network pentest at an associate level. The typical offering includes:

- 12 months access to the Practical Ethical Hacker course  
- One exam attempt plus one free retake with lifetime access to course materials  
- Two full days in a live lab environment  
- Two additional days to write and submit a professional report

Price point and packaging may vary, check the vendor for current details.

---

## 1. Focus on What Matters: Active Directory

You will be dropped straight into an internal Active Directory network via VPN. Rather than spreading yourself thin, prioritize the AD modules in your course material. AD fundamentals, common misconfigurations, and credential hunting will be the highest yield areas during the lab.

---

## 2. Strategy: Enumerate -> Attack -> Re-Enumerate

Pentesting is a simple loop of discovery and exploitation. On exam day, follow this cycle:

### 1) Initial Enumeration
- Identify active hosts, services, and configurations.  
- Collect information from open services, exposed directories, and accessible shares.  
- Note potential attack vectors like weak credentials, outdated software, and misconfigurations.

### 2) Targeted Exploitation
- Use gathered intelligence to guide your actions. Please don't run noisy tools without purpose.  
- When valid credentials or a viable access method are found, execute in a controlled manner and log each step.

### 3) Re-Enumeration with New Access
- Use newly obtained accounts or system access to explore further network segments and resources.  
- Gather additional credentials, tokens, or permissions to expand privileges and reach.

### 4) Continuous Cycle
- Document each success with clear notes and annotated screenshots.  
- If a method doesn't work, please record why it failed, adjust your approach, and continue the loop.

**Pro tip:** Ask yourself "What did that exploit reveal?" after each command. That keeps your efforts purposeful and prevents wasted time.

---

## 3. Polish Your Report

Your report ties everything together. Keep it professional, clear, and evidence-driven. A simple structure works well:

- **Scope & Objectives**  
- **Methodology** (tools, configurations, steps taken)  
- **Findings**  
  - Vulnerability description  
  - Risk rating (Low / Medium / High)  
  - Proof of concept screenshot  
- **Recommendations**  
  - Technical remediation for engineers  
  - Executive summary for leadership

**Screenshot strategy:** Capture output for each exploit and annotate images so reviewers can quickly see what you did and why it matters.

---

## Final Thoughts

Passing the PJPT is not about memorizing commands. It is about building repeatable pentesting habits. Focus on Active Directory, master the enumerate -> attack -> re-enumerate loop, keep a steady lab practice, and deliver a polished report. Do that, and you will pass the exam with confidence and earn a credential you actually worked for.
