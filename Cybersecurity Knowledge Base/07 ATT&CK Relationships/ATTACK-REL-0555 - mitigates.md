---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1037"
target_object: "T1021.005"
stix_relationship_id: "relationship--4f05951e-e480-4ffc-b573-3a7aa3fc4b7c"
---
# Relationship 0555: M1037 — mitigates → T1021.005

**Source object:** [[01 ATT&CK/M1037 - Filter Network Traffic|M1037: Filter Network Traffic]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1021.005 - VNC|T1021.005: VNC]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

VNC defaults to TCP ports 5900 for the server, 5800 for browser access, and 5500 for a viewer in listening mode. Filtering or blocking these ports will inhibit VNC traffic utilizing default ports.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4f05951e-e480-4ffc-b573-3a7aa3fc4b7c`.
