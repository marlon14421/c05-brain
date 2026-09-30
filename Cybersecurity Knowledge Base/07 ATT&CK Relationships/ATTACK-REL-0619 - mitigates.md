---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1042"
target_object: "T1595.003"
stix_relationship_id: "relationship--117756fe-fb41-414d-81ab-63e0bb1ccdc8"
---
# Relationship 0619: M1042 — mitigates → T1595.003

**Source object:** [[01 ATT&CK/M1042 - Disable or Remove Feature or Program|M1042: Disable or Remove Feature or Program]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1595.003 - Wordlist Scanning|T1595.003: Wordlist Scanning]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Remove or disable access to any systems, resources, and infrastructure that are not explicitly required to be available externally.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--117756fe-fb41-414d-81ab-63e0bb1ccdc8`.
