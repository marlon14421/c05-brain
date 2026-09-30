---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0055"
target_object: "T1071.002"
stix_relationship_id: "relationship--3ec8d5a9-77b4-4406-8c0e-9bccaf4d0cea"
---
# Relationship 8185: C0055 — uses → T1071.002

**Source object:** [[01 ATT&CK/C0055 - Quad7 Activity|C0055: Quad7 Activity]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.002 - File Transfer Protocols|T1071.002: File Transfer Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Quad7 Activity](https://attack.mitre.org/campaigns/C0055) has used a File Transfer Protocol (FTP) server to download malicious binaries.(Citation: Microsoft Storm-0940)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3ec8d5a9-77b4-4406-8c0e-9bccaf4d0cea`.
