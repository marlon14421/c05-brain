---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1097"
target_object: "T1140"
stix_relationship_id: "relationship--950d2e53-296a-491e-aadf-8cc5d04df41b"
---
# Relationship 5428: S1097 — uses → T1140

**Source object:** [[01 ATT&CK/S1097 - HUI Loader|S1097: HUI Loader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HUI Loader](https://attack.mitre.org/software/S1097) can decrypt and load files containing malicious payloads.(Citation: SecureWorks BRONZE STARLIGHT Ransomware Operations June 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--950d2e53-296a-491e-aadf-8cc5d04df41b`.
