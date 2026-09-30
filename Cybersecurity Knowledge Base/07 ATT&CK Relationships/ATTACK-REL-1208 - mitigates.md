---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1022"
target_object: "T1548.003"
stix_relationship_id: "relationship--800f4061-3347-4816-a633-179ede275505"
---
# Relationship 1208: M1022 — mitigates → T1548.003

**Source object:** [[01 ATT&CK/M1022 - Restrict File and Directory Permissions|M1022: Restrict File and Directory Permissions]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1548.003 - Sudo and Sudo Caching|T1548.003: Sudo and Sudo Caching]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

The sudoers file should be strictly edited such that passwords are always required and that users can't spawn risky processes as users with higher privilege.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--800f4061-3347-4816-a633-179ede275505`.
