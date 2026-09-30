---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1019"
target_object: "T1212"
stix_relationship_id: "relationship--dbcd1bb0-24c3-465f-8b38-d4827ce6edf2"
---
# Relationship 0420: M1019 — mitigates → T1212

**Source object:** [[01 ATT&CK/M1019 - Threat Intelligence Program|M1019: Threat Intelligence Program]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1212 - Exploitation for Credential Access|T1212: Exploitation for Credential Access]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Develop a robust cyber threat intelligence capability to determine what types and levels of threat may use software exploits and 0-days against a particular organization.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dbcd1bb0-24c3-465f-8b38-d4827ce6edf2`.
