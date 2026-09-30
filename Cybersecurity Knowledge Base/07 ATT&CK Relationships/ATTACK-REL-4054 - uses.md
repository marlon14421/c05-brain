---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9043"
target_object: "T1497"
stix_relationship_id: "relationship--fd10197b-dc82-46b8-b600-0abebdcaa8a5"
---
# Relationship 4054: S9043 — uses → T1497

**Source object:** [[01 ATT&CK/S9043 - Mini Shai-Hulud|S9043: Mini Shai-Hulud]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1497 - Virtualization-Sandbox Evasion|T1497: Virtualization/Sandbox Evasion]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Mini Shai-Hulud](https://attack.mitre.org/software/S9043) has evaded sandbox detection by applying a 1-in-6 probability gate that generates a random number which will only trigger the wiper functionality when the set number outcome is met even in environments that match parameters of a geopolitical target.(Citation: Hunt.io TeamPCP Toolkit MAY 2026)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fd10197b-dc82-46b8-b600-0abebdcaa8a5`.
