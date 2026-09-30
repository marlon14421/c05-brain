---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1197"
target_object: "T1090"
stix_relationship_id: "relationship--660e8d4a-4de9-4566-92d7-0bd7e8e85d19"
---
# Relationship 2930: S1197 — uses → T1090

**Source object:** [[01 ATT&CK/S1197 - GoBear|S1197: GoBear]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090 - Proxy|T1090: Proxy]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[GoBear](https://attack.mitre.org/software/S1197) implements SOCKS5 proxy functionality.(Citation: S2W Troll Stealer 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--660e8d4a-4de9-4566-92d7-0bd7e8e85d19`.
