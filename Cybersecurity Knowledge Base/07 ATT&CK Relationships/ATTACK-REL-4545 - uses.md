---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0005"
target_object: "T1140"
stix_relationship_id: "relationship--25446e74-d461-4113-8ff9-9d6984696680"
---
# Relationship 4545: C0005 — uses → T1140

**Source object:** [[01 ATT&CK/C0005 - Operation Spalax|C0005: Operation Spalax]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

For [Operation Spalax](https://attack.mitre.org/campaigns/C0005), the threat actors used a variety of packers and droppers to decrypt malicious payloads.(Citation: ESET Operation Spalax Jan 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--25446e74-d461-4113-8ff9-9d6984696680`.
