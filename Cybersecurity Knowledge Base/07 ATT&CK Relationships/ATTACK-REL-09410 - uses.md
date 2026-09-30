---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0035"
target_object: "T1003.003"
stix_relationship_id: "relationship--a291d185-31c8-4458-a3fc-9af617af28d9"
---
# Relationship 9410: G0035 — uses → T1003.003

**Source object:** [[01 ATT&CK/G0035 - Dragonfly|G0035: Dragonfly]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1003.003 - NTDS|T1003.003: NTDS]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Dragonfly](https://attack.mitre.org/groups/G0035) has dropped and executed SecretsDump to dump password hashes. They also obtained ntds.dit from domain controllers.(Citation: US-CERT TA18-074A)(Citation: Core Security Impacket)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a291d185-31c8-4458-a3fc-9af617af28d9`.
