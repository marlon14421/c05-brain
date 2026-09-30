---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0221"
target_object: "T1059.003"
stix_relationship_id: "relationship--2f4d2f2e-78a9-46e6-bb2f-5b1be932da42"
---
# Relationship 6025: S0221 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0221 - Umbreon|S0221: Umbreon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Umbreon](https://attack.mitre.org/software/S0221) provides access using both standard facilities like SSH and additional access using its backdoor Espeon, providing a reverse shell upon receipt of a special packet(Citation: Umbreon Trend Micro)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2f4d2f2e-78a9-46e6-bb2f-5b1be932da42`.
