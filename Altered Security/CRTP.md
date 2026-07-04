# CRTP Certification Review: My Experience With Altered Security's Active Directory Certification

I recently completed the **Certified Red Team Professional (CRTP)** certification from **Altered Security**. With Active Directory being such a major focus of my offensive security studies, CRTP was a certification I had been interested in completing for a while.

Going into the course, I already had experience working with Active Directory professionally as a Network Administrator and had completed several Active Directory-focused labs and certifications. I was familiar with tools like `BloodHound`, `PowerView`, `Mimikatz`, and various PowerShell-based enumeration techniques.

Even with that background, CRTP helped reinforce one of the most important lessons in Active Directory security testing:

> **Enumerate everything.**

---

## What is CRTP?

The **Certified Red Team Professional (CRTP)** certification focuses heavily on attacking and abusing Active Directory environments.

The course covers techniques related to:

- Active Directory enumeration
- Privilege escalation
- Credential abuse
- Kerberos attacks
- Delegation
- ACL abuse
- Active Directory trust relationships
- Identifying attack paths through domain environments

Unlike certifications that cover a broad range of penetration testing topics, CRTP stays heavily focused on **Active Directory security and exploitation**.

The exam is a **24-hour hands-on practical assessment** where you are placed into an Active Directory environment and required to identify and exploit attack paths within the domain.

After completing the practical portion, you must document your findings and submit a penetration testing report detailing the techniques used to compromise the environment.

---

## My Background Going Into CRTP

Before starting CRTP, I already had a decent amount of exposure to Active Directory.

Professionally, I work as a **Network Administrator** managing enterprise infrastructure involving Active Directory, Entra ID, Microsoft Defender, VMware, Cisco, and Fortinet technologies.

From an offensive security perspective, I had also completed the **PNPT** and **PJPT** certifications and spent a significant amount of time working through Active Directory labs.

Some of the techniques I had previously practiced included:

- LLMNR and NBT-NS poisoning
- NTLM relay attacks
- AS-REP roasting
- Kerberoasting
- Local administrator password reuse
- Credential dumping
- Active Directory ACL abuse
- Domain trust enumeration
- BloodHound attack path analysis

Because of this, I wasn't completely new to Active Directory attacks going into CRTP.

However, knowing individual techniques and understanding how they connect inside an Active Directory environment are two very different things.

**That is where CRTP was valuable for me.**

---

## The Course Experience

The CRTP training environment is heavily focused on hands-on Active Directory exploitation.

One thing I appreciated about the course was the emphasis on understanding **Active Directory relationships and permissions**.

It's easy to memorize commands.

It's much harder to look at a domain, identify an interesting permission or relationship, and understand how that permission can actually be abused.

CRTP forces you to spend time enumerating the environment and understanding what you are looking at.

`BloodHound` is extremely useful for identifying potential attack paths, but finding a path is only half of the process.

You still need to understand:

- Why the relationship is exploitable
- What permissions you currently have
- What object you can control
- How that control can be converted into additional access

That distinction became one of my biggest takeaways from the course.

---

## The CRTP Exam

The CRTP exam is a **24-hour hands-on Active Directory assessment**.

You are provided access to an environment and must enumerate the domain, identify attack paths, and compromise the required objectives.

**Twenty-four hours sounds like a lot of time.**

It goes quickly.

The biggest mistake you can make is immediately chasing the first interesting attack path you find without properly understanding the environment.

My approach was to spend time enumerating the domain and documenting everything I found before committing too heavily to a specific path.

- Users
- Groups
- Computers
- Sessions
- ACLs
- Delegation configurations
- Kerberos-related opportunities
- Interesting permissions

**Everything matters.**

There were several points during the exam where a technique or method I expected to work simply didn't.

That reinforced another lesson I have learned repeatedly while studying offensive security:

> **Know how to do things more than one way.**

Accessing a system, transferring files, executing tools, and enumerating Active Directory can often be accomplished using multiple techniques.

Sometimes PowerShell doesn't cooperate.

Sometimes a tool gets blocked.

Sometimes the command you have used dozens of times simply doesn't work the way you expect.

Having an alternative method available can save a significant amount of time.

---

## My Biggest CRTP Takeaways

### Enumerate Everything

This is probably the most repeated advice in penetration testing.

There is a reason for that.

Good enumeration early in an assessment can prevent hours of unnecessary backtracking later.

Understanding the environment before attempting exploitation gives you a much better picture of the potential attack paths available.

### Understand the Attack Path

`BloodHound` can show you a path.

That does not mean BloodHound completed the attack for you.

You still need to understand the relationships between objects and how each permission can be abused.

Being able to explain **why an attack path works** is much more valuable than simply copying commands from a cheat sheet.

### Have Multiple Methods

Tools break.

Commands fail.

PowerShell restrictions happen.

Your preferred file transfer method might not work.

Knowing multiple ways to accomplish the same objective is extremely valuable during a time-limited exam.

### Document While You Work

Take screenshots and notes as you progress.

Do not rely on remembering everything after spending hours working through an Active Directory environment.

Good documentation also makes writing the final report significantly easier.

---

## Who Should Take CRTP?

I would recommend CRTP to anyone interested in:

- Active Directory penetration testing
- Internal network penetration testing
- Red teaming
- Windows security
- Understanding Active Directory attack paths

If you are completely new to penetration testing, I would recommend building a basic foundation in **Windows, networking, PowerShell, and Active Directory** before attempting the course.

For someone who already understands basic penetration testing concepts and wants to improve their Active Directory knowledge, CRTP is a great certification.

---

## CRTP and My OSCP Preparation

My current goal is to continue developing my penetration testing and red team skill set.

I am currently studying for the **OSCP**, and CRTP fit well into that process.

While the certifications have different scopes, the enumeration mindset reinforced throughout CRTP directly applies to penetration testing in general.

The biggest thing I continue to learn is that offensive security is rarely about knowing a single command or tool.

It is about understanding the environment, identifying opportunities, adapting when something fails, and continuing to move forward.

> Things will break.  
> Tools won't cooperate.  
> That's okay.  
> **Adapt and keep moving.**

**CRTP down. Back to studying for the OSCP. 🫡**
