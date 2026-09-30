---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1054"
target_object: "T1137"
stix_relationship_id: "relationship--f6f38033-ddd4-418a-ad70-b1198df67fc3"
---
# Relationship 1126: M1054 — mitigates → T1137

**Source object:** [[01 ATT&CK/M1054 - Software Configuration|M1054: Software Configuration]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1137 - Office Application Startup|T1137: Office Application Startup]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

For the Office Test method, create the Registry key used to execute it and set the permissions to "Read Control" to prevent easy access to the key without administrator permissions or requiring Privilege Escalation. (Citation: Palo Alto Office Test Sofacy)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f6f38033-ddd4-418a-ad70-b1198df67fc3`.
