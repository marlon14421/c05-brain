---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0169"
target_object: "T1005"
stix_relationship_id: "relationship--92fb7408-1638-43b7-95a3-0cfeebd7624d"
---
# Relationship 9579: S0169 — uses → T1005

**Source object:** [[01 ATT&CK/S0169 - RawPOS|S0169: RawPOS]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1005 - Data from Local System|T1005: Data from Local System]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RawPOS](https://attack.mitre.org/software/S0169) dumps memory from specific processes on a victim system, parses the dumped files, and scrapes them for credit card data.(Citation: Kroll RawPOS Jan 2017)(Citation: TrendMicro RawPOS April 2015)(Citation: Mandiant FIN5 GrrCON Oct 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--92fb7408-1638-43b7-95a3-0cfeebd7624d`.
