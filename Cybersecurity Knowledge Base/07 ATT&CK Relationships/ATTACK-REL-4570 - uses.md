---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0417"
target_object: "T1113"
stix_relationship_id: "relationship--06b747a6-a3d2-441e-9a24-b79491be3647"
---
# Relationship 4570: S0417 — uses → T1113

**Source object:** [[01 ATT&CK/S0417 - GRIFFON|S0417: GRIFFON]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[GRIFFON](https://attack.mitre.org/software/S0417) has used a screenshot module that can be used to take a screenshot of the remote system.(Citation: SecureList Griffon May 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--06b747a6-a3d2-441e-9a24-b79491be3647`.
