MR. Robot – My First VulnHub Lab Writeup

Platform: VulnHub
Type: Capture The Flag

Introduction

This was my first-ever VulnHub machine, and choosing MR. Robot was the perfect way to start my CTF journey. The box is inspired by the Mr. Robot TV series and focuses heavily on web exploitation, enumeration, and privilege escalation.

This writeup summarizes the approach I took, the challenges I faced, and what I learned along the way

Enumeration

I began with a full scan of the machine to identify open ports and services. The scan revealed a web server, which became my main focus for initial access.

Exploring the website gave several clues related to the show. After checking different sections of the site and investigating available files, I found a path that allowed me to progress further into the machine.

Gaining Foothold

The web application contained hidden directories and files that provided credentials and access points. After some structured enumeration and analysis, I located an entry point that allowed me to gain limited access to the system.

This stage taught me the importance of not overlooking small details, especially in themed machines where hints may be embedded creatively.

Privilege Escalation

With user-level access obtained, I began checking the system for potential privilege escalation paths.

By reviewing file permissions, installed software, and system configurations, I identified a misconfigured component that could be leveraged to move from a low-privileged user to a higher-level account. From there, I continued analyzing the system until I discovered a clear path to full root control.

The escalation phase required patience and careful examination — easily the most challenging (and rewarding) part of the box.

Final Flag

Once I gained root access, I navigated to the appropriate directory and retrieved the final flag.
This moment felt amazing — especially since this was my first completed CTF machine.

What I Learned

Enumeration is the foundation: Missing one small detail can block your entire progress.

Privilege escalation requires creativity: It’s more than running tools — it’s about understanding the system.

Pay attention to themes: In this box, the Mr. Robot references actually guided the process.

Patience matters: Getting stuck is part of the learning experience.

Conclusion

MR. Robot was an excellent introduction to hands-on cybersecurity practice. It pushed me to think critically, stay persistent, and apply multiple concepts across different areas of penetration testing.

Completing this machine boosted my confidence and motivated me to continue tackling more VulnHub and CTF challenges.

If you’re just starting out like me, I highly recommend this box!
