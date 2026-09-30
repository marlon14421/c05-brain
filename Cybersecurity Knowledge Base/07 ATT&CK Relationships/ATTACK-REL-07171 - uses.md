---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0032"
target_object: "T1033"
stix_relationship_id: "relationship--500130c0-d049-4e67-9bcc-d60a5f6dfd4c"
---
# Relationship 7171: G0032 — uses → T1033

**Source object:** [[01 ATT&CK/G0032 - Lazarus Group|G0032: Lazarus Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

Various [Lazarus Group](https://attack.mitre.org/groups/G0032) malware enumerates logged-on users.(Citation: Novetta Blockbuster)(Citation: Novetta Blockbuster Destructive Malware)(Citation: Novetta Blockbuster Loaders)(Citation: Novetta Blockbuster RATs)(Citation: McAfee Lazarus Resurfaces Feb 2018)(Citation: SentinelOne Lazarus macOS July 2020)(Citation: Lazarus APT January 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--500130c0-d049-4e67-9bcc-d60a5f6dfd4c`.
