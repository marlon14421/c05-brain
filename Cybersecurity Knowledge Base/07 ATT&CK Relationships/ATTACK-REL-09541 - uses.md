---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0003"
target_object: "T1573.001"
stix_relationship_id: "relationship--c945e5f2-5622-46ce-8b35-468d41d2af46"
---
# Relationship 9541: S0003 — uses → T1573.001

**Source object:** [[01 ATT&CK/S0003 - RIPTIDE|S0003: RIPTIDE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.001 - Symmetric Cryptography|T1573.001: Symmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT12](https://attack.mitre.org/groups/G0005) has used the [RIPTIDE](https://attack.mitre.org/software/S0003) RAT, which communicates over HTTP with a payload encrypted with RC4.(Citation: Moran 2014)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c945e5f2-5622-46ce-8b35-468d41d2af46`.
