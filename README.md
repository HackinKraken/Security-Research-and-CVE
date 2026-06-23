
# CVE-Research
## My Research-to-CVE Pipeline
Researcher: Steven Amador

Alias & Handle: HackinKraken

*Be sure to follow if you would like to stay updated. I intend to keep searching and improving my skillset.*

#### **I have more narrative write ups available on my website: https://hackinkraken.com**

## CVE-2022-2650 — Improper Restriction of Excessive Authentication Attempts in GitHub repository wger-project/wger prior to 2.2
I came across **wger**, a workout application that had a demo site and allowed for standalone installation. I found the **application** would not block brute-force attacks against the login page. Very simple, very straightforward. This led to my first CVE: `CVE-2022-2650`.

## CVE-2026-39338 — Blind XSS in ChurchCRM Global Search (Current)
I recently decided to channel my studying, which led to my second CVE: `CVE-2026-39338`. This time it was a Blind XSS vulnerability in a search bar where the JS executed in the backend despite receiving an error on the front end, leading to me to exfiltrate valid sessions cookies to a "remote" listener.

# You can read the official details of each CVE below.

| CVE ID | Original Criticality | Post NIST Enrichment Criticality | Link |
|---|---|---|---|
| CVE-2022-2650 | High | Critical | https://nvd.nist.gov/vuln/detail/CVE-2022-2650 |
| CVE-2026-39338 | High | Pending | https://nvd.nist.gov/vuln/detail/CVE-2026-39338 |

