---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0246"
target_object: "T1001.003"
stix_relationship_id: "relationship--9e193b3a-3f21-43aa-b373-6fcec59ff2c7"
---
# Relationship 6242: S0246 — uses → T1001.003

**Source object:** [[01 ATT&CK/S0246 - HARDRAIN|S0246: HARDRAIN]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1001.003 - Protocol or Service Impersonation|T1001.003: Protocol or Service Impersonation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HARDRAIN](https://attack.mitre.org/software/S0246) uses FakeTLS to communicate with its C2 server.(Citation: MAR10135536-F)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9e193b3a-3f21-43aa-b373-6fcec59ff2c7`.
