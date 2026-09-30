---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0245"
target_object: "T1001.003"
stix_relationship_id: "relationship--5292f0c1-e65e-4233-aa97-ab75354d74a9"
---
# Relationship 9265: S0245 — uses → T1001.003

**Source object:** [[01 ATT&CK/S0245 - BADCALL|S0245: BADCALL]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1001.003 - Protocol or Service Impersonation|T1001.003: Protocol or Service Impersonation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BADCALL](https://attack.mitre.org/software/S0245) uses a FakeTLS method during C2.(Citation: Malware Analysis Report 10135536-G)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5292f0c1-e65e-4233-aa97-ab75354d74a9`.
