---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0664"
target_object: "T1068"
stix_relationship_id: "relationship--5c60473c-6195-4aa1-ae10-394bb5f24cf1"
---
# Relationship 6840: S0664 — uses → T1068

**Source object:** [[01 ATT&CK/S0664 - Pandora|S0664: Pandora]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1068 - Exploitation for Privilege Escalation|T1068: Exploitation for Privilege Escalation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Pandora](https://attack.mitre.org/software/S0664) can use CVE-2017-15303 to bypass Windows Driver Signature Enforcement (DSE) protection and load its driver.(Citation: Trend Micro Iron Tiger April 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5c60473c-6195-4aa1-ae10-394bb5f24cf1`.
