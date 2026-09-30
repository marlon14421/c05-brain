---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9007"
target_object: "T1113"
stix_relationship_id: "relationship--7cd4244c-38ef-4396-a76d-0450b7f1a651"
---
# Relationship 8302: S9007 — uses → T1113

**Source object:** [[01 ATT&CK/S9007 - HTTPTroy|S9007: HTTPTroy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HTTPTroy](https://attack.mitre.org/software/S9007) has obtained screen captures leveraging the `screen` command which captures, encrypts and uploads the stolen image to the adversary controlled C2 server.(Citation: Gen Digital Kimsuky HTTPTroy October 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7cd4244c-38ef-4396-a76d-0450b7f1a651`.
