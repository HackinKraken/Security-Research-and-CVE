
# CVE-Research
## My Research-to-CVE Pipeline
Researcher: Steven Amador

Alias & Handle: HackinKraken

*Be sure to follow if you would like to stay updated. I intend to keep searching and improving my skillset.*

## CVE-2022-2650 - Improper Restriction of Excessive Authentication Attempts in GitHub repository wger-project/wger prior to 2.2
In 2022, I was hoping to "get on the map" with my first CVE. I searched through multiple GitHub repos until I came across **wger**, a workout application that had a demo site and allowed for standalone installation. Written in Python, it stood out to me. After a bit of testing and getting a feel for what it's like to do testing with no hand-holding, I found the **application** would not block brute-force attacks against the login page. Very simple, very straightforward. This led to my first CVE: `CVE-2022-2650`.

## CVE-2026-39338 — Blind XSS in ChurchCRM Global Search (Current)
Four years later. But why so long? The truth is, I spent the next few years **trying** to figure things out—personally and professionally. My career took multiple twists and turns where I worked with some good people and some... outright awful. I had to focus on my priorities and what was right in front of me, and that is what I did.
What did I do for four years? A lot.
Career-wise, I've been working in Cloud Security after a year of working as a pentester. During that time, I studied WebApp... a lot. I recently decided to channel my studying, which led to my second CVE: `CVE-2026-39338`. This time it was a Blind XSS vulnerability in a search bar where the JS executed in the backend despite receiving an error on the front end, leading to me to exfiltrate valid sessions cookies to a "remote" listener.

# You can read the official details of each CVE below.

| CVE ID | Original Criticality | Post NIST Enrichment Criticality | Link |
|---|---|---|---|
| CVE-2022-2650 | High | Critical | https://nvd.nist.gov/vuln/detail/CVE-2022-2650 |
| CVE-2026-39338 | High | Pending | https://nvd.nist.gov/vuln/detail/CVE-2026-39338 |

