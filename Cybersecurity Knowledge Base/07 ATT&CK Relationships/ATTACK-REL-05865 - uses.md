---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1044"
target_object: "T1056.001"
stix_relationship_id: "relationship--aaf34dd8-3ce7-4c6a-b4f1-c87dc7262e9f"
---
# Relationship 5865: G1044 — uses → T1056.001

**Source object:** [[01 ATT&CK/G1044 - APT42|G1044: APT42]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.001 - Keylogging|T1056.001: Keylogging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT42](https://attack.mitre.org/groups/G1044) has used custom malware to log keystrokes.(Citation: Mandiant APT42-charms)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--aaf34dd8-3ce7-4c6a-b4f1-c87dc7262e9f`.
