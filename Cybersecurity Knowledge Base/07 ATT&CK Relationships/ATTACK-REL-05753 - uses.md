---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0601"
target_object: "T1613"
stix_relationship_id: "relationship--457ee5f7-ec8f-4990-bfe0-8cf0a6e70b1f"
---
# Relationship 5753: S0601 — uses → T1613

**Source object:** [[01 ATT&CK/S0601 - Hildegard|S0601: Hildegard]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1613 - Container and Resource Discovery|T1613: Container and Resource Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Hildegard](https://attack.mitre.org/software/S0601) has used masscan to search for kubelets and the kubelet API for additional running containers.(Citation: Unit 42 Hildegard Malware)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--457ee5f7-ec8f-4990-bfe0-8cf0a6e70b1f`.
