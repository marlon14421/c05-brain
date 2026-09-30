---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1054"
target_object: "T1137.002"
stix_relationship_id: "relationship--375f4ab4-542f-42f6-9577-f66a6e20f9ca"
---
# Relationship 1274: M1054 — mitigates → T1137.002

**Source object:** [[01 ATT&CK/M1054 - Software Configuration|M1054: Software Configuration]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1137.002 - Office Test|T1137.002: Office Test]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Create the Registry key used to execute it and set the permissions to "Read Control" to prevent easy access to the key without administrator permissions or requiring Privilege Escalation.(Citation: Palo Alto Office Test Sofacy)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--375f4ab4-542f-42f6-9577-f66a6e20f9ca`.
