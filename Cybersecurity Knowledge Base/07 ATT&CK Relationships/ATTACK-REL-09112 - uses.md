---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0583"
target_object: "T1685"
stix_relationship_id: "relationship--5d0accb1-8889-4d96-9eb2-0258548c5b23"
---
# Relationship 9112: S0583 — uses → T1685

**Source object:** [[01 ATT&CK/S0583 - Pysa|S0583: Pysa]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1685 - Disable or Modify Tools|T1685: Disable or Modify Tools]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Pysa](https://attack.mitre.org/software/S0583) has the capability to stop antivirus services and disable Windows Defender.(Citation: CERT-FR PYSA April 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5d0accb1-8889-4d96-9eb2-0258548c5b23`.
