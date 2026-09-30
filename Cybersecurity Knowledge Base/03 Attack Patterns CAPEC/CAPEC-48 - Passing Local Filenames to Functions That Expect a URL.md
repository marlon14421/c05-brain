---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-48"
status: "Draft"
---
# CAPEC-48: Passing Local Filenames to Functions That Expect a URL

**Abstraction:** Standard  
**Catalog severity:** High  
**Catalog likelihood:** High

## Description

This attack relies on client side code to access local files and resources instead of URLs. When the client browser is expecting a URL string, but instead receives a request for a local file, that execution is likely to occur in the browser process space with the browser's authority to local files. The attacker can send the results of this request to the local files out to a site that they control. This attack may be used to steal sensitive authentication data (either local or remote), or to gain system profile information to launch further attacks.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-48 on capec.mitre.org](https://capec.mitre.org/data/definitions/48.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
