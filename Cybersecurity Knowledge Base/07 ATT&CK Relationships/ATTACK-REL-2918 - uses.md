---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0684"
target_object: "T1087.004"
stix_relationship_id: "relationship--51046675-9dcd-416e-a43d-09ae7d589a18"
---
# Relationship 2918: S0684 — uses → T1087.004

**Source object:** [[01 ATT&CK/S0684 - ROADTools|S0684: ROADTools]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1087.004 - Cloud Account|T1087.004: Cloud Account]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[ROADTools](https://attack.mitre.org/software/S0684) can enumerate Azure AD users.(Citation: Roadtools)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--51046675-9dcd-416e-a43d-09ae7d589a18`.
