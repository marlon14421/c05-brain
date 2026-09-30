---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0412"
target_object: "T1071.002"
stix_relationship_id: "relationship--a18f1ae0-dbc8-4f6d-9c88-ab284ce2bf0c"
---
# Relationship 7201: S0412 — uses → T1071.002

**Source object:** [[01 ATT&CK/S0412 - ZxShell|S0412: ZxShell]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.002 - File Transfer Protocols|T1071.002: File Transfer Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ZxShell](https://attack.mitre.org/software/S0412) has used FTP for C2 connections.(Citation: Talos ZxShell Oct 2014)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a18f1ae0-dbc8-4f6d-9c88-ab284ce2bf0c`.
