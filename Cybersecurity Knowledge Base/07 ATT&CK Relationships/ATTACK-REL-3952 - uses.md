---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1227"
target_object: "T1140"
stix_relationship_id: "relationship--fc61d659-2c80-4148-92ff-b689093a49b2"
---
# Relationship 3952: S1227 — uses → T1140

**Source object:** [[01 ATT&CK/S1227 - StarProxy|S1227: StarProxy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[StarProxy](https://attack.mitre.org/software/S1227) has decrypted network packets using a custom algorithm.(Citation: Zscaler)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fc61d659-2c80-4148-92ff-b689093a49b2`.
