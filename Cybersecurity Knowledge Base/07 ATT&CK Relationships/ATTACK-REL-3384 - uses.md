---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9008"
target_object: "T1546.016"
stix_relationship_id: "relationship--af251a47-d612-47ed-8f46-a064bd8ed80f"
---
# Relationship 3384: S9008 — uses → T1546.016

**Source object:** [[01 ATT&CK/S9008 - Shai-Hulud|S9008: Shai-Hulud]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1546.016 - Installer Packages|T1546.016: Installer Packages]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Shai-Hulud](https://attack.mitre.org/software/S9008) has inserted a new lifecycle hook to include `postinstall`.(Citation: Aikido Shai-Hulud September 2025)(Citation: Palo Alto Unit 42 Shai-Hulud November 2025)(Citation: Wiz Shai-Hulud September 2025)(Citation: Socket Shai-Hulud November 2025) [Shai-Hulud](https://attack.mitre.org/software/S9008) has also leveraged the NPM lifecycle hook `preinstall`.(Citation: Netskope Shai-Hulud November 2025)(Citation: Palo Alto Unit 42 Shai-Hulud November 2025)(Citation: Microsoft Shai-Hulud December 2025)(Citation: Socket Shai-Hulud November 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--af251a47-d612-47ed-8f46-a064bd8ed80f`.
