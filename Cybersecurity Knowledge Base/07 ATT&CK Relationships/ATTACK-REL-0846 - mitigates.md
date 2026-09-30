---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1047"
target_object: "T1564.006"
stix_relationship_id: "relationship--23aee030-3467-494e-8262-c32b35355958"
---
# Relationship 0846: M1047 — mitigates → T1564.006

**Source object:** [[01 ATT&CK/M1047 - Audit|M1047: Audit]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1564.006 - Run Virtual Instance|T1564.006: Run Virtual Instance]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Periodically audit virtual machines for abnormalities. On ESXi servers, periodically compare the output of `vim-cmd vmsvc/getallvms`, which lists all VMs in vCenter, and `escxli vm process list | grep Display`, which lists all VMs hosted on ESXi.(Citation: MITRE VMware Abuse 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--23aee030-3467-494e-8262-c32b35355958`.
