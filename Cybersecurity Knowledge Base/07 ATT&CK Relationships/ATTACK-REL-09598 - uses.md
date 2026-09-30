---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9015"
target_object: "T1573.002"
stix_relationship_id: "relationship--732d6f62-11b7-412d-a458-33c0269d2933"
---
# Relationship 9598: S9015 — uses → T1573.002

**Source object:** [[01 ATT&CK/S9015 - BRICKSTORM|S9015: BRICKSTORM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.002 - Asymmetric Cryptography|T1573.002: Asymmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BRICKSTORM](https://attack.mitre.org/software/S9015) has communicated with C2 infrastructure via TLS.(Citation: CrowdStrike BRICKSTORM WARP PANDA UNC5221 December 2025)(Citation: CISA BRICKSTORM UNC5221 AR25-338A February 2026)(Citation: Picus Security BRICKSTORM UNC5221 October 2025)(Citation: Resecurity UNC5221 BRICKSTORM F5 Big-IP October 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--732d6f62-11b7-412d-a458-33c0269d2933`.
