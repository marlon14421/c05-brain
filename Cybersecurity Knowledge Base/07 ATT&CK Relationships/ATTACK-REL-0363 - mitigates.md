---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1050"
target_object: "T1218"
stix_relationship_id: "relationship--1f1de0ea-581b-4b41-953f-1b8f552f84e7"
---
# Relationship 0363: M1050 — mitigates → T1218

**Source object:** [[01 ATT&CK/M1050 - Exploit Protection|M1050: Exploit Protection]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1218 - System Binary Proxy Execution|T1218: System Binary Proxy Execution]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Microsoft's Enhanced Mitigation Experience Toolkit (EMET) Attack Surface Reduction (ASR) feature can be used to block methods of using using trusted binaries to bypass application control.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1f1de0ea-581b-4b41-953f-1b8f552f84e7`.
