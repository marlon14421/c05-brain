---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1132"
target_object: "T1059.003"
stix_relationship_id: "relationship--94d3cffe-544e-4a9b-aa58-72d7ed19aa33"
---
# Relationship 4547: S1132 — uses → T1059.003

**Source object:** [[01 ATT&CK/S1132 - IPsec Helper|S1132: IPsec Helper]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[IPsec Helper](https://attack.mitre.org/software/S1132) can run arbitrary commands passed to it through cmd.exe .(Citation: SentinelOne Agrius 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--94d3cffe-544e-4a9b-aa58-72d7ed19aa33`.
