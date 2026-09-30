---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0638"
target_object: "T1489"
stix_relationship_id: "relationship--4f5efe16-ce46-4e37-9c9d-d45b14d1ab4c"
---
# Relationship 9861: S0638 — uses → T1489

**Source object:** [[01 ATT&CK/S0638 - Babuk|S0638: Babuk]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1489 - Service Stop|T1489: Service Stop]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Babuk](https://attack.mitre.org/software/S0638) can stop specific services related to backups.(Citation: Sogeti CERT ESEC Babuk March 2021)(Citation: McAfee Babuk February 2021)(Citation: Trend Micro Ransomware February 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4f5efe16-ce46-4e37-9c9d-d45b14d1ab4c`.
