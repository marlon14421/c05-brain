---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1029"
target_object: "T1072"
stix_relationship_id: "relationship--e4236234-0fd7-426f-b55a-d32364e3a64e"
---
# Relationship 0211: M1029 — mitigates → T1072

**Source object:** [[01 ATT&CK/M1029 - Remote Data Storage|M1029: Remote Data Storage]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1072 - Software Deployment Tools|T1072: Software Deployment Tools]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

If the application deployment system can be configured to deploy only signed binaries, then ensure that the trusted signing certificates are not co-located with the application deployment system and are instead located on a system that cannot be accessed remotely or to which remote access is tightly controlled.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e4236234-0fd7-426f-b55a-d32364e3a64e`.
