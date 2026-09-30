---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0049"
target_object: "T1083"
stix_relationship_id: "relationship--1b3cc0cb-de43-405b-bfa5-f0bececabf8c"
---
# Relationship 9829: S0049 — uses → T1083

**Source object:** [[01 ATT&CK/S0049 - GeminiDuke|S0049: GeminiDuke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[GeminiDuke](https://attack.mitre.org/software/S0049) collects information from the victim, including installed drivers, programs previously executed by users, programs and services configured to automatically run at startup, files and folders present in any user's home folder, files and folders present in any user's My Documents, programs installed to the Program Files folder, and recently accessed files, folders, and programs.(Citation: F-Secure The Dukes)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1b3cc0cb-de43-405b-bfa5-f0bececabf8c`.
