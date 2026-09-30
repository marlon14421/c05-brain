---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1059"
target_object: "T1070.004"
stix_relationship_id: "relationship--c3c78b2e-a53e-4020-8fba-6e63c73e0b76"
---
# Relationship 3329: S1059 — uses → T1070.004

**Source object:** [[01 ATT&CK/S1059 - metaMain|S1059: metaMain]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[metaMain](https://attack.mitre.org/software/S1059) has deleted collected items after uploading the content to its C2 server.(Citation: SentinelLabs Metador Sept 2022)(Citation: SentinelLabs Metador Technical Appendix Sept 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c3c78b2e-a53e-4020-8fba-6e63c73e0b76`.
