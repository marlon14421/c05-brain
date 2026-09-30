---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1221"
target_object: "T1027.013"
stix_relationship_id: "relationship--462f46ec-2a7a-419a-8a62-06543e79d75f"
---
# Relationship 4634: S1221 — uses → T1027.013

**Source object:** [[01 ATT&CK/S1221 - MOPSLED|S1221: MOPSLED]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[MOPSLED](https://attack.mitre.org/software/S1221) can encrypt configuration files with a custom ChaCha20 algorithm.(Citation: Google Cloud Mandiant UNC3886 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--462f46ec-2a7a-419a-8a62-06543e79d75f`.
