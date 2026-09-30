---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0061"
target_object: "T1098.004"
stix_relationship_id: "relationship--b5bee386-9f09-4911-922e-8975b22f6d9c"
---
# Relationship 9642: C0061 — uses → T1098.004

**Source object:** [[01 ATT&CK/C0061 - Operation Digital Eye|C0061: Operation Digital Eye]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1098.004 - SSH Authorized Keys|T1098.004: SSH Authorized Keys]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Operation Digital Eye](https://attack.mitre.org/campaigns/C0061), threat actors used SSH access enabled by authorized_keys files for remote execution.(Citation: sentinelone operationDigitalEye Dec 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b5bee386-9f09-4911-922e-8975b22f6d9c`.
