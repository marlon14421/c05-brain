---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1022"
target_object: "T1053"
stix_relationship_id: "relationship--7a0efacc-7005-4f1e-9fb8-047d8b703cf8"
---
# Relationship 0759: M1022 — mitigates → T1053

**Source object:** [[01 ATT&CK/M1022 - Restrict File and Directory Permissions|M1022: Restrict File and Directory Permissions]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1053 - Scheduled Task-Job|T1053: Scheduled Task/Job]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Restrict access by setting directory and file permissions that are not specific to users or privileged accounts.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7a0efacc-7005-4f1e-9fb8-047d8b703cf8`.
