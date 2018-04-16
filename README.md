# Project 8 - Pentesting Live Targets

Time spent: 5 hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:
* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each version of the site has been given two of the six vulnerabilities. (In other words, all six of the exploits should be assignable to one of the sites.)

## Blue

Vulnerability #1: SQL Injection (SQLI)
<a href="https://imgur.com/EyTJcjm"><img src="https://i.imgur.com/EyTJcjm.gif" title="source: imgur.com" /></a>

Vulnerability #2: Session Hijacking
<a href="https://imgur.com/n7S2ndZ"><img src="https://i.imgur.com/n7S2ndZ.gif" title="source: imgur.com" /></a>


## Green

Vulnerability #1: Username Enumeration
<a href="https://imgur.com/jw9Mruc"><img src="https://i.imgur.com/jw9Mruc.gif" title="source: imgur.com" /></a>

Vulnerability #2: Cross-Site Scripting (XSS)
<a href="https://imgur.com/jkUahJI"><img src="https://i.imgur.com/jkUahJI.gif" title="source: imgur.com" /></a>


## Red

Vulnerability #1: Insecure Direct Object Reference (IDOR)
<a href="https://imgur.com/ZsuJysk"><img src="https://i.imgur.com/ZsuJysk.gif" title="source: imgur.com" /></a>

Vulnerability #2: __________________


## Notes

I found the CSRF exploit to be quite difficult. I couldn't get it to work on the Red site. I tried posting an HTML form via the Contact
section, but it didn't seem to have the effect I expected.
