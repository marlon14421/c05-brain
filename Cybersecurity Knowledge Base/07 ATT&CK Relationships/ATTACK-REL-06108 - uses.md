---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0050"
target_object: "T1583.006"
stix_relationship_id: "relationship--c16c1ef2-2356-4987-bd9e-2cdaa007281a"
---
# Relationship 6108: G0050 — uses → T1583.006

**Source object:** [[01 ATT&CK/G0050 - APT32|G0050: APT32]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1583.006 - Web Services|T1583.006: Web Services]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT32](https://attack.mitre.org/groups/G0050) has set up Dropbox, Amazon S3, and Google Drive to host malicious downloads.(Citation: Volexity Ocean Lotus November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c16c1ef2-2356-4987-bd9e-2cdaa007281a`.
