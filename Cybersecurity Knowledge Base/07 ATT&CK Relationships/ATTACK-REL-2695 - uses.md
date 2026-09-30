---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0016"
target_object: "T1133"
stix_relationship_id: "relationship--8bc0dbc4-f84b-448a-95f9-f6b0ae56f256"
---
# Relationship 2695: G0016 — uses → T1133

**Source object:** [[01 ATT&CK/G0016 - APT29|G0016: APT29]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1133 - External Remote Services|T1133: External Remote Services]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[APT29](https://attack.mitre.org/groups/G0016) has used compromised identities to access networks via VPNs and Citrix.(Citation: NCSC APT29 July 2020)(Citation: Mandiant APT29 Microsoft 365 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8bc0dbc4-f84b-448a-95f9-f6b0ae56f256`.
