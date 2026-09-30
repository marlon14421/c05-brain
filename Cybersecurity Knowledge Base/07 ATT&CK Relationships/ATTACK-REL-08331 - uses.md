---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0439"
target_object: "T1001"
stix_relationship_id: "relationship--3bca1b9e-c598-494a-9471-0121734e7c79"
---
# Relationship 8331: S0439 — uses → T1001

**Source object:** [[01 ATT&CK/S0439 - Okrum|S0439: Okrum]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1001 - Data Obfuscation|T1001: Data Obfuscation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

Okrum leverages the HTTP protocol for C2 communication, while hiding the actual messages in the Cookie and Set-Cookie headers of the HTTP requests.(Citation: ESET Okrum July 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3bca1b9e-c598-494a-9471-0121734e7c79`.
