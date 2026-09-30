---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0154"
target_object: "T1203"
stix_relationship_id: "relationship--de676fc0-0b1f-4392-a84b-f412c660d89a"
---
# Relationship 9564: S0154 — uses → T1203

**Source object:** [[01 ATT&CK/S0154 - Cobalt Strike|S0154: Cobalt Strike]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1203 - Exploitation for Client Execution|T1203: Exploitation for Client Execution]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Cobalt Strike](https://attack.mitre.org/software/S0154) can exploit Oracle Java vulnerabilities for execution, including CVE-2011-3544, CVE-2013-2465, CVE-2012-4681, and CVE-2013-2460.(Citation: Talos Cobalt Strike September 2020)(Citation: Cobalt Strike Manual 4.3 November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--de676fc0-0b1f-4392-a84b-f412c660d89a`.
