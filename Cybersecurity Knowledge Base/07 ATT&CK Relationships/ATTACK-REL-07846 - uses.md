---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1035"
target_object: "T1027"
stix_relationship_id: "relationship--7dfc877a-4563-4c7f-91e0-b5f5adfcb873"
---
# Relationship 7846: S1035 — uses → T1027

**Source object:** [[01 ATT&CK/S1035 - Small Sieve|S1035: Small Sieve]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027 - Obfuscated Files or Information|T1027: Obfuscated Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Small Sieve](https://attack.mitre.org/software/S1035) has the ability to use a custom hex byte swapping encoding scheme combined with an obfuscated Base64 function to protect program strings and Telegram credentials.(Citation: NCSC GCHQ Small Sieve Jan 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7dfc877a-4563-4c7f-91e0-b5f5adfcb873`.
