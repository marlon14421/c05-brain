---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1013"
target_object: "T1105"
stix_relationship_id: "relationship--0bde7434-49de-40c4-906c-fc5f3bfc6d16"
---
# Relationship 6917: S1013 — uses → T1105

**Source object:** [[01 ATT&CK/S1013 - ZxxZ|S1013: ZxxZ]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ZxxZ](https://attack.mitre.org/software/S1013) can download and execute additional files.(Citation: Cisco Talos Bitter Bangladesh May 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0bde7434-49de-40c4-906c-fc5f3bfc6d16`.
