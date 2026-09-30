---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0394"
target_object: "T1573.001"
stix_relationship_id: "relationship--603d13cd-f6f7-4321-99db-3d3326878de4"
---
# Relationship 8654: S0394 — uses → T1573.001

**Source object:** [[01 ATT&CK/S0394 - HiddenWasp|S0394: HiddenWasp]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.001 - Symmetric Cryptography|T1573.001: Symmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HiddenWasp](https://attack.mitre.org/software/S0394) uses an RC4-like algorithm with an already computed PRGA generated key-stream for network communication.(Citation: Intezer HiddenWasp Map 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--603d13cd-f6f7-4321-99db-3d3326878de4`.
