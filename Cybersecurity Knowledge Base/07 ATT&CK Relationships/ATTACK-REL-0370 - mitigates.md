---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1042"
target_object: "T1218.015"
stix_relationship_id: "relationship--3329382e-c40f-44a2-82c3-fb1479c3b6d2"
---
# Relationship 0370: M1042 — mitigates → T1218.015

**Source object:** [[01 ATT&CK/M1042 - Disable or Remove Feature or Program|M1042: Disable or Remove Feature or Program]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1218.015 - Electron Applications|T1218.015: Electron Applications]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Remove or deny access to unnecessary and potentially vulnerable software and features to prevent abuse by adversaries. Many native binaries may not be necessary within a given environment: for example, consider disabling the Node.js integration in all renderers that display remote content to protect users by limiting adversaries’ power to plant malicious JavaScript within Electron applications.(Citation: Electron Security 2)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3329382e-c40f-44a2-82c3-fb1479c3b6d2`.
