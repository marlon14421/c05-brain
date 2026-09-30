---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0263"
target_object: "T1543.003"
stix_relationship_id: "relationship--cd63c221-6dc1-4b88-ab82-8f64493cbacd"
---
# Relationship 8189: S0263 — uses → T1543.003

**Source object:** [[01 ATT&CK/S0263 - TYPEFRAME|S0263: TYPEFRAME]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1543.003 - Windows Service|T1543.003: Windows Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TYPEFRAME](https://attack.mitre.org/software/S0263) variants can add malicious DLL modules as new services.[TYPEFRAME](https://attack.mitre.org/software/S0263) can also delete services from the victim’s machine.(Citation: US-CERT TYPEFRAME June 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cd63c221-6dc1-4b88-ab82-8f64493cbacd`.
