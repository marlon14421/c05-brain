---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0194"
target_object: "T1558.003"
stix_relationship_id: "relationship--aaa0e944-7158-4baa-b45b-c687f7b161b5"
---
# Relationship 8256: S0194 — uses → T1558.003

**Source object:** [[01 ATT&CK/S0194 - PowerSploit|S0194: PowerSploit]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1558.003 - Kerberoasting|T1558.003: Kerberoasting]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PowerSploit](https://attack.mitre.org/software/S0194)'s Invoke-Kerberoast module can request service tickets and return crackable ticket hashes.(Citation: PowerSploit Invoke Kerberoast)(Citation: Harmj0y Kerberoast Nov 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--aaa0e944-7158-4baa-b45b-c687f7b161b5`.
