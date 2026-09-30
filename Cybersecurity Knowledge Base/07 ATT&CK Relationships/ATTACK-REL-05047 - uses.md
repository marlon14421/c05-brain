---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1060"
target_object: "T1205.001"
stix_relationship_id: "relationship--16a59f96-4c5c-4625-a776-61162ac9c6c1"
---
# Relationship 5047: S1060 — uses → T1205.001

**Source object:** [[01 ATT&CK/S1060 - Mafalda|S1060: Mafalda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1205.001 - Port Knocking|T1205.001: Port Knocking]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mafalda](https://attack.mitre.org/software/S1060) can use port-knocking to authenticate itself to another implant called Cryshell to establish an indirect connection to the C2 server.(Citation: SentinelLabs Metador Sept 2022)(Citation: SentinelLabs Metador Technical Appendix Sept 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--16a59f96-4c5c-4625-a776-61162ac9c6c1`.
