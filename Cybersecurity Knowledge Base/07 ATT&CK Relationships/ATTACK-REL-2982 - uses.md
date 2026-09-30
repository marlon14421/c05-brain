---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0601"
target_object: "T1102"
stix_relationship_id: "relationship--81fcae09-a738-4922-9553-aad21e2b940b"
---
# Relationship 2982: S0601 — uses → T1102

**Source object:** [[01 ATT&CK/S0601 - Hildegard|S0601: Hildegard]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1102 - Web Service|T1102: Web Service]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Hildegard](https://attack.mitre.org/software/S0601) has downloaded scripts from GitHub.(Citation: Unit 42 Hildegard Malware)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--81fcae09-a738-4922-9553-aad21e2b940b`.
