---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0221"
target_object: "T1095"
stix_relationship_id: "relationship--c4aec6a5-2c11-45a2-8c79-8cccf85179cb"
---
# Relationship 9537: S0221 — uses → T1095

**Source object:** [[01 ATT&CK/S0221 - Umbreon|S0221: Umbreon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1095 - Non-Application Layer Protocol|T1095: Non-Application Layer Protocol]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Umbreon](https://attack.mitre.org/software/S0221) provides access to the system via SSH or any other protocol that uses PAM to authenticate.(Citation: Umbreon Trend Micro)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c4aec6a5-2c11-45a2-8c79-8cccf85179cb`.
