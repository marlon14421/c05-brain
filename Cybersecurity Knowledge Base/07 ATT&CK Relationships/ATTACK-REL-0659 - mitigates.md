---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1043"
target_object: "T1601.001"
stix_relationship_id: "relationship--7349c449-f6cd-44cd-858d-93c29320d7f0"
---
# Relationship 0659: M1043 — mitigates → T1601.001

**Source object:** [[01 ATT&CK/M1043 - Credential Access Protection|M1043: Credential Access Protection]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1601.001 - Patch System Image|T1601.001: Patch System Image]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Some embedded network devices are capable of storing passwords for local accounts in either plain-text or encrypted formats. Ensure that, where available, local passwords are always encrypted, per vendor recommendations. (Citation: Cisco IOS Software Integrity Assurance - Credentials Management)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7349c449-f6cd-44cd-858d-93c29320d7f0`.
