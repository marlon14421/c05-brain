---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0038"
target_object: "T1218.007"
stix_relationship_id: "relationship--16ad2735-61b3-4cb4-8f23-439df70715c8"
---
# Relationship 6588: S0038 — uses → T1218.007

**Source object:** [[01 ATT&CK/S0038 - Duqu|S0038: Duqu]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.007 - Msiexec|T1218.007: Msiexec]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Duqu](https://attack.mitre.org/software/S0038) has used msiexec to execute malicious Windows Installer packages. Additionally, a PROPERTY=VALUE pair containing a 56-bit encryption key has been used to decrypt the main payload from the installer packages.(Citation: Kaspersky Duqu 2.0)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--16ad2735-61b3-4cb4-8f23-439df70715c8`.
