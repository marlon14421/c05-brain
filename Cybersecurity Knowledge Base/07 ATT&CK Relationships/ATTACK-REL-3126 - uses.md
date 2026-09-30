---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0683"
target_object: "T1619"
stix_relationship_id: "relationship--9f2ee173-a4b2-45d9-8dfe-537f1fc82ef4"
---
# Relationship 3126: S0683 — uses → T1619

**Source object:** [[01 ATT&CK/S0683 - Peirates|S0683: Peirates]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1619 - Cloud Storage Object Discovery|T1619: Cloud Storage Object Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Peirates](https://attack.mitre.org/software/S0683) can list AWS S3 buckets.(Citation: Peirates GitHub)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9f2ee173-a4b2-45d9-8dfe-537f1fc82ef4`.
