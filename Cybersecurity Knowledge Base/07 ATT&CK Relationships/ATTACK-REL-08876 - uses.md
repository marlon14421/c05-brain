---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0050"
target_object: "T1039"
stix_relationship_id: "relationship--3e7c9978-4db1-4ee1-ae27-640acee5a543"
---
# Relationship 8876: S0050 — uses → T1039

**Source object:** [[01 ATT&CK/S0050 - CosmicDuke|S0050: CosmicDuke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1039 - Data from Network Shared Drive|T1039: Data from Network Shared Drive]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CosmicDuke](https://attack.mitre.org/software/S0050) steals user files from network shared drives with file extensions and keywords that match a predefined list.(Citation: F-Secure Cosmicduke)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3e7c9978-4db1-4ee1-ae27-640acee5a543`.
