---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0070"
target_object: "T1056.001"
stix_relationship_id: "relationship--ab7faed6-3c50-4b04-a31b-ac2c933a51ef"
---
# Relationship 5339: S0070 — uses → T1056.001

**Source object:** [[01 ATT&CK/S0070 - HTTPBrowser|S0070: HTTPBrowser]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.001 - Keylogging|T1056.001: Keylogging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HTTPBrowser](https://attack.mitre.org/software/S0070) is capable of capturing keystrokes on victims.(Citation: Dell TG-3390)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ab7faed6-3c50-4b04-a31b-ac2c933a51ef`.
