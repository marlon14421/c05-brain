---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0184"
target_object: "T1132.001"
stix_relationship_id: "relationship--b9109cd5-1b13-4376-a761-b68302879351"
---
# Relationship 3263: S0184 — uses → T1132.001

**Source object:** [[01 ATT&CK/S0184 - POWRUNER|S0184: POWRUNER]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1132.001 - Standard Encoding|T1132.001: Standard Encoding]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[POWRUNER](https://attack.mitre.org/software/S0184) can use base64 encoded C2 communications.(Citation: FireEye APT34 Dec 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b9109cd5-1b13-4376-a761-b68302879351`.
