---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1021"
target_object: "T1071.004"
stix_relationship_id: "relationship--68ddf3bf-bf01-4de5-8b0e-e00db5a8ee7e"
---
# Relationship 5940: S1021 — uses → T1071.004

**Source object:** [[01 ATT&CK/S1021 - DnsSystem|S1021: DnsSystem]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.004 - DNS|T1071.004: DNS]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DnsSystem](https://attack.mitre.org/software/S1021) can direct queries to custom DNS servers and return C2 commands using TXT records.(Citation: Zscaler Lyceum DnsSystem June 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--68ddf3bf-bf01-4de5-8b0e-e00db5a8ee7e`.
