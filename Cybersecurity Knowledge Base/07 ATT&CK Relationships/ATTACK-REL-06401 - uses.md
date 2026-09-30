---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9009"
target_object: "T1552.005"
stix_relationship_id: "relationship--9c12bad3-408b-473d-86b9-cf179edce3e2"
---
# Relationship 6401: S9009 — uses → T1552.005

**Source object:** [[01 ATT&CK/S9009 - TruffleHog|S9009: TruffleHog]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1552.005 - Cloud Instance Metadata API|T1552.005: Cloud Instance Metadata API]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TruffleHog](https://attack.mitre.org/software/S9009) can query the AWS and GCP metadata endpoints for instances and service credentials.(Citation: Black Hills Information Security TruffleHog January 2024)(Citation: Github TruffleSecurity Trufflehog April 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9c12bad3-408b-473d-86b9-cf179edce3e2`.
