---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1210"
target_object: "T1074.001"
stix_relationship_id: "relationship--c66dddb1-0003-4af8-9887-5642964e0fd0"
---
# Relationship 8759: S1210 — uses → T1074.001

**Source object:** [[01 ATT&CK/S1210 - Sagerunex|S1210: Sagerunex]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1074.001 - Local Data Staging|T1074.001: Local Data Staging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Sagerunex](https://attack.mitre.org/software/S1210) gathers host information and stages it locally as a RAR file prior to exfiltration.(Citation: Cisco LotusBlossom 2025) [Sagerunex](https://attack.mitre.org/software/S1210) stores logged data in an encrypted file located at `%TEMP%/TS_FB56.tmp` during execution.(Citation: Symantec Bilbug 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c66dddb1-0003-4af8-9887-5642964e0fd0`.
