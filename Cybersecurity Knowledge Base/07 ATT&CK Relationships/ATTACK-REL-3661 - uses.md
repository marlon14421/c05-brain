---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1112"
target_object: "T1140"
stix_relationship_id: "relationship--d86a36a9-fce9-4147-b375-292d6b617769"
---
# Relationship 3661: S1112 — uses → T1140

**Source object:** [[01 ATT&CK/S1112 - STEADYPULSE|S1112: STEADYPULSE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[STEADYPULSE](https://attack.mitre.org/software/S1112) can URL decode key/value pairs sent over C2.(Citation: Mandiant Pulse Secure Zero-Day April 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d86a36a9-fce9-4147-b375-292d6b617769`.
