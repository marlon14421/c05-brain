---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1304"
status: "Draft"
---
# CWE-1304: Improperly Preserved Integrity of Hardware Configuration State During a Power Save/Restore Operation

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific

## Description

The product performs a power save/restore operation, but it does not ensure that the integrity of the configuration state is maintained and/or verified between the beginning and ending of the operation.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Inside the IP, incorporate integrity checking on the configuration state via a cryptographic hash. The hash can be protected inside the IP such as by storing it in internal registers which never lose power. Before powering down, the IP performs a hash of the configuration and saves it in these persistent registers. Upon restore, the IP performs a hash of the saved configuration and compares it with the saved hash. If they do not match, then the IP should not trust the configuration.
- **Integration:** Outside the IP, incorporate integrity checking of the configuration state via a trusted agent. Before powering down, the trusted agent performs a hash of the configuration and saves the hash in persistent storage. Upon restore, the IP requests the trusted agent validate its current configuration. If the configuration hash is invalid, then the IP should not trust the configuration.
- **Integration:** Outside the IP, incorporate a protected environment that prevents undetected modification of the configuration state by untrusted agents. Before powering down, a trusted agent saves the IP's configuration state in this protected location that only it is privileged to. Upon restore, the trusted agent loads the saved state into the IP.

## Related weaknesses

- CWE-284 (ChildOf)
- CWE-345 (PeerOf)
- CWE-1271 (PeerOf)

## Source

- [CWE-1304 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1304.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
