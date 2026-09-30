---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0040"
target_object: "T1071.001"
stix_relationship_id: "relationship--d09c5595-27c1-4ada-9502-1012710b35a2"
---
# Relationship 7858: C0040 — uses → T1071.001

**Source object:** [[01 ATT&CK/C0040 - APT41 DUST|C0040: APT41 DUST]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT41 DUST](https://attack.mitre.org/campaigns/C0040) used HTTPS for command and control.(Citation: Google Cloud APT41 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d09c5595-27c1-4ada-9502-1012710b35a2`.
