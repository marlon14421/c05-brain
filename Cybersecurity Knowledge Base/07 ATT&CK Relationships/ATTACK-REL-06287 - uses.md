---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0002"
target_object: "T1003.002"
stix_relationship_id: "relationship--7f04a14f-ab65-4ad5-9d67-a4b509ba8087"
---
# Relationship 6287: S0002 — uses → T1003.002

**Source object:** [[01 ATT&CK/S0002 - Mimikatz|S0002: Mimikatz]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1003.002 - Security Account Manager|T1003.002: Security Account Manager]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mimikatz](https://attack.mitre.org/software/S0002) performs credential dumping to obtain account and password information useful in gaining access to additional systems and enterprise network resources. It contains functionality to acquire information about credentials in many ways, including from the SAM table.(Citation: Deply Mimikatz)(Citation: GitHub Mimikatz lsadump Module)(Citation: Directory Services Internals DPAPI Backup Keys Oct 2015)(Citation: NCSC Joint Report Public Tools)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7f04a14f-ab65-4ad5-9d67-a4b509ba8087`.
