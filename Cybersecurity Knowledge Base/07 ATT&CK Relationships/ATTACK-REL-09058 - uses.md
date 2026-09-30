---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9042"
target_object: "T1555.006"
stix_relationship_id: "relationship--fed5bab3-c121-4857-834a-07f9f05f2955"
---
# Relationship 9058: S9042 — uses → T1555.006

**Source object:** [[01 ATT&CK/S9042 - CanisterWorm|S9042: CanisterWorm]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1555.006 - Cloud Secrets Management Stores|T1555.006: Cloud Secrets Management Stores]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CanisterWorm](https://attack.mitre.org/software/S9042) has gathered credentials from Amazon Web Services (AWS), Google Cloud Platform (GCP), and Microsoft Azure.(Citation: FBI TeamPCP JUL 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fed5bab3-c121-4857-834a-07f9f05f2955`.
