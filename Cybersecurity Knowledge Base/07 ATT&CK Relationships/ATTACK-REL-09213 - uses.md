---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0016"
target_object: "T1027.013"
stix_relationship_id: "relationship--a3b40306-fafa-47e6-9164-fbd75e04b645"
---
# Relationship 9213: C0016 — uses → T1027.013

**Source object:** [[01 ATT&CK/C0016 - Operation Dust Storm|C0016: Operation Dust Storm]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Operation Dust Storm](https://attack.mitre.org/campaigns/C0016), the threat actors encoded some payloads with a single-byte XOR, both skipping the key itself and zeroing in an attempt to avoid exposing the key; other payloads were Base64-encoded.(Citation: Cylance Dust Storm)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a3b40306-fafa-47e6-9164-fbd75e04b645`.
