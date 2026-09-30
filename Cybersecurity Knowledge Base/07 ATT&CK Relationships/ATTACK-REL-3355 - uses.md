---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0229"
target_object: "T1083"
stix_relationship_id: "relationship--0188b7af-d060-4715-baf2-ad69333482dc"
---
# Relationship 3355: S0229 — uses → T1083

**Source object:** [[01 ATT&CK/S0229 - Orz|S0229: Orz]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Orz](https://attack.mitre.org/software/S0229) can gather victim drive information.(Citation: Proofpoint Leviathan Oct 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0188b7af-d060-4715-baf2-ad69333482dc`.
