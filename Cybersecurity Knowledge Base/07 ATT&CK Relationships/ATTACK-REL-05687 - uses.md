---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0099"
target_object: "T1586.003"
stix_relationship_id: "relationship--e7ec67f5-d78a-4ba6-b9f7-b0ca43773ac1"
---
# Relationship 5687: G0099 — uses → T1586.003

**Source object:** [[01 ATT&CK/G0099 - APT-C-36|G0099: APT-C-36]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1586.003 - Cloud Accounts|T1586.003: Cloud Accounts]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT-C-36](https://attack.mitre.org/groups/G0099) has used compromised Google Drive accounts including one associated with a Colombian government organization.(Citation: Recorded Future TAG-144 AUG 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e7ec67f5-d78a-4ba6-b9f7-b0ca43773ac1`.
