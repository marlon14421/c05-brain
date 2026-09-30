---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0129"
target_object: "T1052.001"
stix_relationship_id: "relationship--6f8d9c8d-750d-40c2-9722-c000b1efda13"
---
# Relationship 9708: G0129 — uses → T1052.001

**Source object:** [[01 ATT&CK/G0129 - Mustang Panda|G0129: Mustang Panda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1052.001 - Exfiltration over USB|T1052.001: Exfiltration over USB]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mustang Panda](https://attack.mitre.org/groups/G0129) has used a customized [PlugX](https://attack.mitre.org/software/S0013) variant which could exfiltrate documents from air-gapped networks.(Citation: Avira Mustang Panda January 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6f8d9c8d-750d-40c2-9722-c000b1efda13`.
