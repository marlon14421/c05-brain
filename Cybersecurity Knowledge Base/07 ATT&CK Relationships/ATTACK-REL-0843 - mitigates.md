---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1028"
target_object: "T1542.005"
stix_relationship_id: "relationship--46ace311-9be9-4d4a-8ef0-fc2c0659fba9"
---
# Relationship 0843: M1028 — mitigates → T1542.005

**Source object:** [[01 ATT&CK/M1028 - Operating System Configuration|M1028: Operating System Configuration]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1542.005 - TFTP Boot|T1542.005: TFTP Boot]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Follow vendor device hardening best practices to disable unnecessary and unused features and services, avoid using default configurations and passwords, and introduce logging and auditing for detection.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--46ace311-9be9-4d4a-8ef0-fc2c0659fba9`.
