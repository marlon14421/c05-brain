---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1314"
status: "Draft"
---
# CWE-1314: Missing Write Protection for Parametric Data Values

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Sensor Hardware

## Description

The device does not write-protect the parametric data values for sensors that scale the sensor value, allowing untrusted software to manipulate the apparent result and potentially damage hardware or cause operational failure.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Access controls for sensor blocks should ensure that only trusted software is allowed to change threshold limits and sensor parametric data.

## Related weaknesses

- CWE-862 (ChildOf)
- CWE-1299 (PeerOf)

## Source

- [CWE-1314 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1314.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
