---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-6"
status: "Incomplete"
---
# CWE-6: J2EE Misconfiguration: Insufficient Session-ID Length

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Java, Web Based, Web Server

## Description

The J2EE application is configured to use an insufficient session ID length.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Session identifiers should be at least 128 bits long to prevent brute-force session guessing. A shorter session identifier leaves the application open to brute-force session guessing attacks.
- **Implementation:** A lower bound on the number of valid session identifiers that are available to be guessed is the number of users that are active on a site at any given moment. However, any users that abandon their sessions without logging out will increase this number. (This is one of many good reasons to have a short inactive session timeout.) With a 64 bit session identifier, assume 32 bits of entropy. For a large web site, assume that the attacker can try 1,000 guesses per second and that there are 10,000 valid session identifiers at any given moment. Given these assumptions, the expected time for an attacker to successfully guess a valid session identifier is less than 4 minutes. Now assume a 128 bit session identifier that provides 64 bits of entropy. With a very large web site, an attacker might try 10,000 guesses per second with 100,000 valid session identifiers available to be guessed. Given these assumptions, the expected time for an attacker to successfully guess a valid session identifier is greater than 292 years.

## Related weaknesses

- CWE-334 (ChildOf)

## Source

- [CWE-6 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/6.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
