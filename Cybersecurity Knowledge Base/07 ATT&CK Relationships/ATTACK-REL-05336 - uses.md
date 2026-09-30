---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0591"
target_object: "T1125"
stix_relationship_id: "relationship--63c952f9-1fec-46db-a2f3-f87114180f25"
---
# Relationship 5336: S0591 — uses → T1125

**Source object:** [[01 ATT&CK/S0591 - ConnectWise|S0591: ConnectWise]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1125 - Video Capture|T1125: Video Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ConnectWise](https://attack.mitre.org/software/S0591) can record video on remote hosts.(Citation: Anomali Static Kitten February 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--63c952f9-1fec-46db-a2f3-f87114180f25`.
