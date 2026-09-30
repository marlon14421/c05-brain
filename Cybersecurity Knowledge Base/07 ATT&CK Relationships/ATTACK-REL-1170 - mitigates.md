---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1047"
target_object: "T1095"
stix_relationship_id: "relationship--8ad2d1c5-aa94-4c32-94c8-8ffb9d11f54a"
---
# Relationship 1170: M1047 — mitigates → T1095

**Source object:** [[01 ATT&CK/M1047 - Audit|M1047: Audit]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1095 - Non-Application Layer Protocol|T1095: Non-Application Layer Protocol]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Periodically investigate ESXi hosts for open VMCI ports. Running the `lsof -A` command and inspecting results with a type of `SOCKET_VMCI` will reveal processes that have open VMCI ports.(Citation: Google Cloud Threat Intelligence ESXi Hardening 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8ad2d1c5-aa94-4c32-94c8-8ffb9d11f54a`.
