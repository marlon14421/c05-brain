---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0677"
target_object: "T1136.003"
stix_relationship_id: "relationship--7a5c8052-723b-47e1-943f-0731b9177730"
---
# Relationship 9034: S0677 — uses → T1136.003

**Source object:** [[01 ATT&CK/S0677 - AADInternals|S0677: AADInternals]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1136.003 - Cloud Account|T1136.003: Cloud Account]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[AADInternals](https://attack.mitre.org/software/S0677) can create new Azure AD users.(Citation: AADInternals Documentation)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7a5c8052-723b-47e1-943f-0731b9177730`.
