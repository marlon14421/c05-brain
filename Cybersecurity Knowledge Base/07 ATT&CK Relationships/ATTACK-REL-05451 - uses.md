---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1001"
target_object: "T1204.002"
stix_relationship_id: "relationship--36693ec3-9b3c-4129-af32-b8372c75211c"
---
# Relationship 5451: G1001 — uses → T1204.002

**Source object:** [[01 ATT&CK/G1001 - HEXANE|G1001: HEXANE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HEXANE](https://attack.mitre.org/groups/G1001) has relied on victim's executing malicious file attachments delivered via email or embedded within actor-controlled websites to deliver malware.(Citation: SecureWorks August 2019)(Citation: Dragos Hexane)(Citation: ClearSky Siamesekitten August 2021)(Citation: Zscaler Lyceum DnsSystem June 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--36693ec3-9b3c-4129-af32-b8372c75211c`.
