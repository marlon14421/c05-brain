---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0589"
target_object: "T1140"
stix_relationship_id: "relationship--aafa7447-cb73-4309-ac75-5326ab0d1079"
---
# Relationship 3671: S0589 — uses → T1140

**Source object:** [[01 ATT&CK/S0589 - Sibot|S0589: Sibot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Sibot](https://attack.mitre.org/software/S0589) can decrypt data received from a C2 and save to a file.(Citation: MSTIC NOBELIUM Mar 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--aafa7447-cb73-4309-ac75-5326ab0d1079`.
