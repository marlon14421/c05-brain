---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1021"
target_object: "T1041"
stix_relationship_id: "relationship--185bd112-5e1f-4059-9e42-b8b80874e8f2"
---
# Relationship 8842: S1021 — uses → T1041

**Source object:** [[01 ATT&CK/S1021 - DnsSystem|S1021: DnsSystem]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1041 - Exfiltration Over C2 Channel|T1041: Exfiltration Over C2 Channel]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DnsSystem](https://attack.mitre.org/software/S1021) can exfiltrate collected data to its C2 server.(Citation: Zscaler Lyceum DnsSystem June 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--185bd112-5e1f-4059-9e42-b8b80874e8f2`.
