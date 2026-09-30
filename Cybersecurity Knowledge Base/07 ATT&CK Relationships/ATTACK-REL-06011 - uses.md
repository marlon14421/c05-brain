---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0357"
target_object: "T1003.003"
stix_relationship_id: "relationship--6d0fb103-d6f6-4259-a62f-296735020176"
---
# Relationship 6011: S0357 — uses → T1003.003

**Source object:** [[01 ATT&CK/S0357 - Impacket|S0357: Impacket]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1003.003 - NTDS|T1003.003: NTDS]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

SecretsDump and [Mimikatz](https://attack.mitre.org/software/S0002) modules within [Impacket](https://attack.mitre.org/software/S0357) can perform credential dumping to obtain account and password information from NTDS.dit.(Citation: Impacket Tools)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6d0fb103-d6f6-4259-a62f-296735020176`.
