---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0043"
target_object: "T1071.001"
stix_relationship_id: "relationship--2b2cdb6b-c23c-4792-8cfb-8c4d9279a186"
---
# Relationship 5855: S0043 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0043 - BUBBLEWRAP|S0043: BUBBLEWRAP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BUBBLEWRAP](https://attack.mitre.org/software/S0043) can communicate using HTTP or HTTPS.(Citation: FireEye admin@338)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2b2cdb6b-c23c-4792-8cfb-8c4d9279a186`.
