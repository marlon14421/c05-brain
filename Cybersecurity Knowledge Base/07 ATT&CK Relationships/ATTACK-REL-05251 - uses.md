---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0652"
target_object: "T1518"
stix_relationship_id: "relationship--d1a2cd6c-1c7b-4c1a-9416-106e7951642c"
---
# Relationship 5251: S0652 — uses → T1518

**Source object:** [[01 ATT&CK/S0652 - MarkiRAT|S0652: MarkiRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1518 - Software Discovery|T1518: Software Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MarkiRAT](https://attack.mitre.org/software/S0652) can check for the Telegram installation directory by enumerating the files on disk.(Citation: Kaspersky Ferocious Kitten Jun 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d1a2cd6c-1c7b-4c1a-9416-106e7951642c`.
