---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0180"
target_object: "T1140"
stix_relationship_id: "relationship--fd2f1a44-2ae7-4df0-b53c-42bc96af2da1"
---
# Relationship 7737: S0180 — uses → T1140

**Source object:** [[01 ATT&CK/S0180 - Volgmer|S0180: Volgmer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Volgmer](https://attack.mitre.org/software/S0180) deobfuscates its strings and APIs once its executed.(Citation: US-CERT Volgmer 2 Nov 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fd2f1a44-2ae7-4df0-b53c-42bc96af2da1`.
