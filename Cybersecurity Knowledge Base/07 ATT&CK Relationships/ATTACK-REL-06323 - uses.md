---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0683"
target_object: "T1530"
stix_relationship_id: "relationship--2cf91706-674a-4ae0-8a4c-0d8d43eb6e1a"
---
# Relationship 6323: S0683 — uses → T1530

**Source object:** [[01 ATT&CK/S0683 - Peirates|S0683: Peirates]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1530 - Data from Cloud Storage|T1530: Data from Cloud Storage]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Peirates](https://attack.mitre.org/software/S0683) can dump the contents of AWS S3 buckets. It can also retrieve service account tokens from kOps buckets in Google Cloud Storage or S3.(Citation: Peirates GitHub)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2cf91706-674a-4ae0-8a4c-0d8d43eb6e1a`.
