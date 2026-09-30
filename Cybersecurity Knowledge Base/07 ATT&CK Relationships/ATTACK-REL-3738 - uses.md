---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0518"
target_object: "T1140"
stix_relationship_id: "relationship--fe2eb5b7-7ae1-4df1-a49e-ad13f50510e8"
---
# Relationship 3738: S0518 — uses → T1140

**Source object:** [[01 ATT&CK/S0518 - PolyglotDuke|S0518: PolyglotDuke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[PolyglotDuke](https://attack.mitre.org/software/S0518) can use a custom algorithm to decrypt strings used by the malware.(Citation: ESET Dukes October 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fe2eb5b7-7ae1-4df1-a49e-ad13f50510e8`.
