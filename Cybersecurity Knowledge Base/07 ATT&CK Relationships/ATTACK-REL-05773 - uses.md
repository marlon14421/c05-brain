---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0016"
target_object: "T1595.002"
stix_relationship_id: "relationship--9bc0b5e1-d9be-4303-b396-df990c664c4b"
---
# Relationship 5773: G0016 — uses → T1595.002

**Source object:** [[01 ATT&CK/G0016 - APT29|G0016: APT29]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1595.002 - Vulnerability Scanning|T1595.002: Vulnerability Scanning]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT29](https://attack.mitre.org/groups/G0016) has conducted widespread scanning of target environments to identify vulnerabilities for exploit.(Citation: Cybersecurity Advisory SVR TTP May 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9bc0b5e1-d9be-4303-b396-df990c664c4b`.
