# 🎯 My Experience Earning the SANS Penetration Testing & Ethical Hacking Graduate Certificate

My path through the SANS Penetration Testing & Ethical Hacking Graduate Certificate was a little different from the standard course progression.

Before starting the program, I had completed the SANS Applied Cybersecurity Certificate (ACS). During the ACS program, I earned several GIAC certifications, including the **GIAC Certified Incident Handler (GCIH)** and **GIAC Web Application Penetration Tester (GWAPT)**.

When I decided to continue my SANS education through the Penetration Testing & Ethical Hacking Graduate Certificate, I was able to use my previous GCIH and GWAPT coursework as substitutions for the first and third course requirements.

This worked out perfectly for what I wanted to accomplish.

The two certifications I really wanted to pursue were the **GIAC Penetration Tester (GPEN)** and the **GIAC Exploit Researcher and Advanced Penetration Tester (GXPN)**.

At the same time, I was working as an Application Security Analyst at AbbVie through the Department of Defense SkillBridge program. This was my first opportunity to gain real-world, hands-on cybersecurity experience outside of the military and played a major role in pushing me toward offensive security.

This post covers my experience pursuing GPEN and GXPN, gaining practical application security experience, and ultimately completing the SANS Penetration Testing & Ethical Hacking Graduate Certificate.

---

## 🛡️ How Application Security Introduced Me to Offensive Security

When I started the graduate certificate program, I was also completing a DoD SkillBridge internship as an Application Security Analyst at AbbVie.

Going into the position, I had spent plenty of time working through cybersecurity courses, certifications, and hands-on labs. SkillBridge gave me the opportunity to apply some of that knowledge in an actual enterprise environment.

More importantly, the team introduced me to offensive security from a professional perspective.

During my time in application security, I had the opportunity to perform my own security testing against applications, validate vulnerabilities, and conduct remediation retesting after development teams implemented fixes.

I also gained experience with the other side of penetration testing that is sometimes overlooked when working through labs and CTFs: **the process around the technical testing**.

I worked with PlexTrac for report writing and documenting technical findings. I helped onboard applications into the security testing process and participated in meetings with application owners and development teams.

Those conversations were just as valuable as the technical testing.

Finding a vulnerability is only one part of the job.

You also need to understand the application, explain why the vulnerability matters, communicate the potential impact, and work with the people responsible for fixing it.

Working directly with application owners and developers helped me understand how important communication is in offensive security.

A finding can be technically accurate, but if you cannot clearly explain the risk or provide useful context to the people responsible for remediation, you are limiting the value of your work.

That experience completely changed the way I looked at penetration testing.

I realized I enjoyed the entire process.

The enumeration.

The testing.

Finding something that behaves differently than expected.

Validating whether a vulnerability is actually exploitable.

Documenting the finding.

And then working with developers and application owners through the remediation and retesting process.

That was when offensive security really started becoming the direction I wanted to pursue.

---

## 🧭 Why I Chose the Penetration Testing & Ethical Hacking Graduate Certificate

After completing the Applied Cybersecurity Certificate, I knew I wanted to continue developing my offensive security skills.

My experience at AbbVie had given me real-world exposure to application security and security testing, while my personal labs and certification studies continued pushing me deeper into penetration testing.

I did not necessarily need another broad introduction to cybersecurity.

I wanted to go deeper. 🐇

The SANS Penetration Testing & Ethical Hacking Graduate Certificate gave me an opportunity to focus specifically on offensive security while working toward two certifications that had become major goals of mine: GPEN and GXPN.

Being able to substitute my previous GCIH and GWAPT coursework meant I could focus on the two areas I wanted to develop the most.

**Enterprise penetration testing and advanced exploitation.**

GPEN aligned directly with the penetration testing methodology I was beginning to apply professionally.

GXPN was different.

GXPN represented the technical depth I wanted to eventually reach.

I knew SEC660 would push me outside of my comfort zone, which was exactly why I wanted to take it.

---

## 🔎 SEC560 and the GPEN

SEC560 was the course I had been looking forward to the most when entering the program.

The course focuses heavily on enterprise penetration testing and walks through the penetration testing process from reconnaissance and enumeration through exploitation and post-exploitation.

Topics included:

* 🔭 Reconnaissance and target discovery
* 🔎 Network and service enumeration
* 🔑 Password attacks
* 🌐 Web application testing
* 💥 Exploitation
* 🏢 Active Directory attacks
* 🔀 Pivoting and tunneling
* 🖥️ Post-exploitation

One of the biggest things SEC560 reinforced for me was something that continues to come up throughout offensive security:

**Enumerate everything. 🔎**

It is easy to become focused on finding an exploit or immediately gaining a shell.

However, taking the time to properly understand the environment can save a significant amount of time later.

What services are running?

What systems can communicate with each other?

What users exist?

Are credentials being reused?

What networks can the compromised host access?

The more information you collect, the more potential attack paths become visible.

One of my favorite parts of SEC560 was working through segmented networks and learning how to pivot through compromised systems.

Compromising a host does not always mean you have reached your objective.

Sometimes that system is simply your entry point into another network.

Understanding how to route traffic, proxy tools, and continue enumeration through compromised systems helped me better understand how penetration tests can progress through larger environments.

SEC560 also reinforced the importance of knowing multiple ways to accomplish the same task.

Tools break. 🔨

Payloads get blocked. 🚫

Services behave differently than expected. 🤷🏻‍♂️

The method you expect to work sometimes simply does not.

Knowing multiple ways to transfer files, access systems, enumerate services, and execute commands can save a massive amount of time.

The GPEN exam included both traditional GIAC questions and CyberLive labs requiring hands-on technical work.

By the end of SEC560, I felt significantly more comfortable approaching an unfamiliar network, enumerating the environment, and building an attack path based on the information available.

---

## 🧠 SEC660 and the GXPN

GXPN was the certification I was most interested in pursuing, but it was also the one I knew would challenge me the most.

SEC660 pushed much deeper into the technical side of penetration testing and exploitation.

Topics included:

* 🌐 Advanced network attacks
* 🐍 Python for penetration testing
* 💥 Fuzzing
* 🐧 Linux exploitation
* 🪟 Windows exploitation
* 📚 Stack-based buffer overflows
* 🔗 Return-oriented programming
* 🛡️ Memory protections
* 🐛 Debugging
* 💻 Exploit development

Before SEC660, most of my offensive security experience focused on identifying vulnerabilities and using existing techniques or exploits to gain access.

SEC660 changed the way I looked at vulnerabilities.

Instead of simply asking:

> "Is this vulnerable?"

I started asking:

> "Why is this vulnerable?" 🤔

That difference completely changes how you approach exploitation.

Working with debuggers and analyzing application behavior at a lower level forces you to understand what is actually happening.

You begin looking at registers.

You analyze the stack.

You track memory addresses.

You identify where application execution changes.

You determine what protections are enabled and how those protections affect exploitation.

Exploit development was easily the most challenging part of the course for me.

There were plenty of moments where I had to reread material, rebuild labs, and work through the same process multiple times before the concepts started to connect.

The biggest lesson I took from SEC660 was that advanced technical problems become significantly more manageable when you break them into smaller problems. 🧩

You do not immediately "write an exploit."

You identify the crash.

You determine control.

You analyze bad characters.

You examine memory protections.

You identify usable instructions.

You build the exploit one step at a time.

That mindset applies to much more than exploit development.

GXPN was one of the most technically challenging certifications I had pursued, but it was also one of the most rewarding. 🫡

---

## ⚔️ GPEN vs. GXPN

GPEN and GXPN are both penetration testing certifications, but the courses felt completely different.

GPEN focuses heavily on **how to conduct a penetration test**.

GXPN focuses much more on **understanding and developing advanced exploitation techniques**.

SEC560 helped improve my methodology.

SEC660 challenged my technical depth.

GPEN taught me to better understand the environment and identify attack paths.

GXPN taught me to look deeper into vulnerabilities and understand why exploitation works.

If I had to summarize the difference:

> **GPEN teaches you how to attack an environment.**
>
> **GXPN teaches you how to attack the technology itself.**

Both courses were valuable, but for completely different reasons.

---

## 📚 The SANS Learning Experience

SANS courses are extremely dense.

There is a massive amount of information packed into each course, and attempting to memorize everything is unrealistic.

My approach was to focus on understanding the concepts and building an index that allowed me to quickly locate detailed information when needed.

My indexes generally included:

* 📝 Topic
* 📖 Book number
* 🔢 Page number
* 💻 Tool or command
* 📌 Short description

I also created separate sections for commands and tools that appeared frequently throughout the course.

However, an index should support your knowledge rather than replace it.

CyberLive questions require you to actually interact with systems and tools.

Knowing that a topic exists on a specific page is not very helpful if you do not understand how to use the tool or interpret the output.

The labs were easily the most valuable part of each course. 🧪

I rebuilt labs multiple times and experimented outside of the exact steps provided in the workbook.

If a command worked, I wanted to understand why.

If something failed, I wanted to understand what broke.

That curiosity helped me retain significantly more information than simply following the lab instructions.

---

## 💭 Was the Graduate Certificate Worth It?

For me, absolutely. 💯

The timing of the program could not have worked out much better.

I was gaining professional application security experience through SkillBridge while simultaneously working through advanced penetration testing coursework with SANS.

At AbbVie, I was learning how security testing works within an enterprise.

I was performing tests, validating vulnerabilities, documenting findings, participating in application onboarding, meeting with application owners and developers, and conducting remediation retesting.

Through SANS, I was continuing to build the technical skills behind the testing.

The combination of professional experience and structured technical training helped connect a lot of concepts for me.

GPEN strengthened my penetration testing methodology and enterprise attack skills.

GXPN pushed me into advanced exploitation and exploit development.

The program did not magically make me an expert penetration tester.

There is still an enormous amount to learn.

If anything, completing the program showed me how deep offensive security actually goes. 🐇

However, I walked away with a much stronger technical foundation and a clear understanding of the direction I wanted to take my career.

---

## 🚀 What's Next?

Completing the SANS Penetration Testing & Ethical Hacking Graduate Certificate and earning GPEN and GXPN was a major milestone for me.

My experience in application security introduced me to offensive security in a professional environment.

SANS helped me continue building the technical skills.

Now, my focus is continuing to gain practical penetration testing experience and expanding my knowledge of Active Directory, web application security, and advanced exploitation.

I am currently continuing my OSCP studies and spending as much time as possible working through labs and vulnerable environments. 🧪

Certifications are great milestones, but the learning does not stop when the exam ends.

There will always be another tool. 🔧

Another technique. 🧠

Another vulnerability. 🐛

Another rabbit hole. 🐇

And that is exactly why I enjoy offensive security. 🫡
