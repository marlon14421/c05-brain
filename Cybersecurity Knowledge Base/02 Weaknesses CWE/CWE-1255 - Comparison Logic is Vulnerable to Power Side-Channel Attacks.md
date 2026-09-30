---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1255"
status: "Draft"
---
# CWE-1255: Comparison Logic is Vulnerable to Power Side-Channel Attacks

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific

## Description

A device's real time power consumption may be monitored during security token evaluation and the information gleaned may be used to determine the value of the reference token.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** The design phase must consider each check of a security token against a standard and the amount of power consumed during the check of a good token versus a bad token. The alternative is an all at once check where a retry counter is incremented PRIOR to the check.
- **Architecture and Design:** Another potential mitigation is to parallelize shifting of secret data (see example 2 below). Note that the wider the bus the more effective the result.
- **Architecture and Design:** An additional potential mitigation is to add random data to each crypto operation then subtract it out afterwards. This is highly effective but costly in performance, area, and power consumption. It also requires a random number generator.
- **Implementation:** If the architecture is unable to prevent the attack, using filtering components may reduce the ability to implement an attack, however, consideration must be given to the physical removal of the filter elements.
- **Integration:** During integration, avoid use of a single secret for an extended period (e.g. frequent key updates). This limits the amount of data compromised but at the cost of complexity of use.

## Related weaknesses

- CWE-1300 (ChildOf)
- CWE-1259 (PeerOf)

## Source

- [CWE-1255 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1255.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
