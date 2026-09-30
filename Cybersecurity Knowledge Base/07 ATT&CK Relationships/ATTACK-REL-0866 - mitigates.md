---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1015"
target_object: "T1003.006"
stix_relationship_id: "relationship--7b641542-852b-47c0-a604-f13998adb892"
---
# Relationship 0866: M1015 — mitigates → T1003.006

**Source object:** [[01 ATT&CK/M1015 - Active Directory Configuration|M1015: Active Directory Configuration]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1003.006 - DCSync|T1003.006: DCSync]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Manage the access control list for "Replicating Directory Changes" and other permissions associated with domain controller replication.(Citation: ADSecurity Mimikatz DCSync)(Citation: Microsoft Replication ACL)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7b641542-852b-47c0-a604-f13998adb892`.
