---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0559"
target_object: "T1001.002"
stix_relationship_id: "relationship--f01cbea5-8528-45e8-afdf-d1f382980d8a"
---
# Relationship 4161: S0559 — uses → T1001.002

**Source object:** [[01 ATT&CK/S0559 - SUNBURST|S0559: SUNBURST]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1001.002 - Steganography|T1001.002: Steganography]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[SUNBURST](https://attack.mitre.org/software/S0559) C2 data attempted to appear as benign XML related to .NET assemblies or as a faux JSON blob.(Citation: FireEye SUNBURST Backdoor December 2020)(Citation: FireEye SUNBURST Additional Details Dec 2020)(Citation: Symantec Sunburst Sending Data January 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f01cbea5-8528-45e8-afdf-d1f382980d8a`.
