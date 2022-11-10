# Pen Testing Live Targets

Time spent: **X** hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:

* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each color is vulnerable to only 2 of the 6 possible exploits. First discover which color has the specific vulnerability, then write a short description of how to exploit it, and finally demonstrate it using screenshots compiled into a GIF.

## Blue

Vulnerability #1: SQL Injection (SQLi)

There is not a sanitizing method to avoid injecting a sql command instead of the proper Salesperson's ID Number.

<img src="SQL Injection.gif">


## Green

Vulnerability #1:Username Enumeration

Description: Developer forgot to keep span tag class the same when username is or is not found, leading to vulnerability

<img src="User enumeration.gif">

Vulnerability #2:Cross-Site Scripting

Description: XXS Script was aloowed tu input in the feedback panel

<img src="Cross-Site Scripting (XSS).gif">
## Red

Vulnerability #1: Insecure Direct Object Reference

Description: Attacker get access to the hidden user's accounts that the attacker is not permitted to view.

<img src="Insecure Direct Object Reference.gif">

Vulnerability #2: Cross-Site Request Forgery

Description: Coment Allows loading responses onto iframes

<img src="Cross-Site Request Forgery (CSRF) .gif">

## Notes

Describe any challenges encountered while doing the work
