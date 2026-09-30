---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1021"
target_object: "T1005"
stix_relationship_id: "relationship--931e3af1-d38d-46eb-8c5d-d394510e2df1"
---
# Relationship 9232: S1021 — uses → T1005

**Source object:** [[01 ATT&CK/S1021 - DnsSystem|S1021: DnsSystem]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1005 - Data from Local System|T1005: Data from Local System]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DnsSystem](https://attack.mitre.org/software/S1021) can upload files from infected machines after receiving a command with `uploaddd` in the string.(Citation: Zscaler Lyceum DnsSystem June 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--931e3af1-d38d-46eb-8c5d-d394510e2df1`.
