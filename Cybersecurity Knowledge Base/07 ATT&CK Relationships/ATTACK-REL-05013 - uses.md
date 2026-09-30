---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1222"
target_object: "T1102.002"
stix_relationship_id: "relationship--0f1582a7-f9d3-4397-bab7-57fbb9a16ebd"
---
# Relationship 5013: S1222 — uses → T1102.002

**Source object:** [[01 ATT&CK/S1222 - RIFLESPINE|S1222: RIFLESPINE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1102.002 - Bidirectional Communication|T1102.002: Bidirectional Communication]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RIFLESPINE](https://attack.mitre.org/software/S1222) can retrieve C2 commands from an encrypted file on Google Drive then upload the results of command execution back to Google Drive.(Citation: Google Cloud Mandiant UNC3886 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0f1582a7-f9d3-4397-bab7-57fbb9a16ebd`.
