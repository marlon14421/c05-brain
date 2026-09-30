---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0061"
target_object: "S9028"
stix_relationship_id: "relationship--cfa2ddce-4982-43ad-80ad-8246a9f8966c"
---
# Relationship 5244: C0061 — uses → S9028

**Source object:** [[01 ATT&CK/C0061 - Operation Digital Eye|C0061: Operation Digital Eye]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S9028 - PHPsert|S9028: PHPsert]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Operation Digital Eye](https://attack.mitre.org/campaigns/C0061), threat actors deployed [PHPsert](https://attack.mitre.org/software/S9028) to execution and to maintain access.(Citation: sentinelone operationDigitalEye Dec 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cfa2ddce-4982-43ad-80ad-8246a9f8966c`.
