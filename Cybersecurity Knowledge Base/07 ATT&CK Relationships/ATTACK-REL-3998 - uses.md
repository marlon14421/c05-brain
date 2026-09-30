---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9010"
target_object: "T1027.018"
stix_relationship_id: "relationship--796b5e76-298f-49e3-b93e-53ecfbb2a1ce"
---
# Relationship 3998: S9010 — uses → T1027.018

**Source object:** [[01 ATT&CK/S9010 - GlassWorm|S9010: GlassWorm]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.018 - Invisible Unicode|T1027.018: Invisible Unicode]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[GlassWorm](https://attack.mitre.org/software/S9010) has utilized invisible Unicode Private Use Area (PUA) characters to obfuscate its malicious code so that it does not render in code editors.(Citation: Koi Glassworm New Tricks December 2025)(Citation: Koi Glassworm InvisibleCode October 2025)(Citation: Aikido GlassWorm October 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--796b5e76-298f-49e3-b93e-53ecfbb2a1ce`.
