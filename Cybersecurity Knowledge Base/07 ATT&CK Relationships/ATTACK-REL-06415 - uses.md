---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0058"
target_object: "S0029"
stix_relationship_id: "relationship--1195fdb7-59c3-4426-ba2d-ac86d079ddf9"
---
# Relationship 6415: C0058 — uses → S0029

**Source object:** [[01 ATT&CK/C0058 - SharePoint ToolShell Exploitation|C0058: SharePoint ToolShell Exploitation]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0029 - PsExec|S0029: PsExec]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Microsoft SharePoint Exploit JUL 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1195fdb7-59c3-4426-ba2d-ac86d079ddf9`.
