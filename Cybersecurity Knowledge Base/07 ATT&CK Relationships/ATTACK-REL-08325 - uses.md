---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0061"
target_object: "T1588.002"
stix_relationship_id: "relationship--3a20f6f1-0e1b-4d8e-8461-eb41e4c6b5da"
---
# Relationship 8325: G0061 — uses → T1588.002

**Source object:** [[01 ATT&CK/G0061 - FIN8|G0061: FIN8]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1588.002 - Tool|T1588.002: Tool]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FIN8](https://attack.mitre.org/groups/G0061) has used open-source tools such as [Impacket](https://attack.mitre.org/software/S0357) for targeting efforts.(Citation: Bitdefender Sardonic Aug 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3a20f6f1-0e1b-4d8e-8461-eb41e4c6b5da`.
