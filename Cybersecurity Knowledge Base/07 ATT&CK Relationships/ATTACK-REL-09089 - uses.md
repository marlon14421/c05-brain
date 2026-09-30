---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0640"
target_object: "T1083"
stix_relationship_id: "relationship--431043b7-f0e8-411b-8eec-0d602867b028"
---
# Relationship 9089: S0640 — uses → T1083

**Source object:** [[01 ATT&CK/S0640 - Avaddon|S0640: Avaddon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Avaddon](https://attack.mitre.org/software/S0640) has searched for specific files prior to encryption.(Citation: Arxiv Avaddon Feb 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--431043b7-f0e8-411b-8eec-0d602867b028`.
