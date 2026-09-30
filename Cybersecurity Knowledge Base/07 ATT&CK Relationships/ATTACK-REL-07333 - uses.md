---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0387"
target_object: "T1555.003"
stix_relationship_id: "relationship--e49cb6bd-78c8-4826-a292-a7c5d3096d2b"
---
# Relationship 7333: S0387 — uses → T1555.003

**Source object:** [[01 ATT&CK/S0387 - KeyBoy|S0387: KeyBoy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1555.003 - Credentials from Web Browsers|T1555.003: Credentials from Web Browsers]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[KeyBoy](https://attack.mitre.org/software/S0387) attempts to collect passwords from browsers.(Citation: Rapid7 KeyBoy Jun 2013)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e49cb6bd-78c8-4826-a292-a7c5d3096d2b`.
