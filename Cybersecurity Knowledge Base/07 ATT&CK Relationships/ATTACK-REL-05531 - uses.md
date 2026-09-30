---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0113"
target_object: "T1555"
stix_relationship_id: "relationship--5c84cfe2-a395-47c6-831a-4491f8585a00"
---
# Relationship 5531: S0113 — uses → T1555

**Source object:** [[01 ATT&CK/S0113 - Prikormka|S0113: Prikormka]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1555 - Credentials from Password Stores|T1555: Credentials from Password Stores]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

A module in [Prikormka](https://attack.mitre.org/software/S0113) collects passwords stored in applications installed on the victim.(Citation: ESET Operation Groundbait)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5c84cfe2-a395-47c6-831a-4491f8585a00`.
