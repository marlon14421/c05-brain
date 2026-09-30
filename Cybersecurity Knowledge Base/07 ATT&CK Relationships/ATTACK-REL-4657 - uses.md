---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9031"
target_object: "T1678"
stix_relationship_id: "relationship--fdf235f6-3ecc-4b78-bc6b-90dc0e922efd"
---
# Relationship 4657: S9031 — uses → T1678

**Source object:** [[01 ATT&CK/S9031 - AshTag|S9031: AshTag]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1678 - Delay Execution|T1678: Delay Execution]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[AshTag](https://attack.mitre.org/software/S9031) can use a set sleep time to delay C2 beaconing.(Citation: Palo Alto Ashen Lepus DEC 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fdf235f6-3ecc-4b78-bc6b-90dc0e922efd`.
