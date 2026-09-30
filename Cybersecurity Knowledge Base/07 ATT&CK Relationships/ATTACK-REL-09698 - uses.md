---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0002"
target_object: "T1550.003"
stix_relationship_id: "relationship--76037b22-a3e4-40d3-bd56-699d1ea4e97e"
---
# Relationship 9698: S0002 — uses → T1550.003

**Source object:** [[01 ATT&CK/S0002 - Mimikatz|S0002: Mimikatz]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1550.003 - Pass the Ticket|T1550.003: Pass the Ticket]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mimikatz](https://attack.mitre.org/software/S0002)’s LSADUMP::DCSync and KERBEROS::PTT modules implement the three steps required to extract the krbtgt account hash and create/use Kerberos tickets.(Citation: Adsecurity Mimikatz Guide)(Citation: AdSecurity Kerberos GT Aug 2015)(Citation: Harmj0y DCSync Sept 2015)(Citation: NCSC Joint Report Public Tools)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--76037b22-a3e4-40d3-bd56-699d1ea4e97e`.
