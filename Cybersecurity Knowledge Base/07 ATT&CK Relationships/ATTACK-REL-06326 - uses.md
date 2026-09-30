---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0096"
target_object: "T1071.002"
stix_relationship_id: "relationship--2cd69fd0-d5ad-41db-aaee-fd58e46bfaaa"
---
# Relationship 6326: G0096 — uses → T1071.002

**Source object:** [[01 ATT&CK/G0096 - APT41|G0096: APT41]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.002 - File Transfer Protocols|T1071.002: File Transfer Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT41](https://attack.mitre.org/groups/G0096) used exploit payloads that initiate download via [ftp](https://attack.mitre.org/software/S0095).(Citation: FireEye APT41 March 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2cd69fd0-d5ad-41db-aaee-fd58e46bfaaa`.
