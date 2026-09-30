---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0070"
target_object: "T1071.004"
stix_relationship_id: "relationship--7eb3d9b7-8058-4d26-9196-b9a79716c5f9"
---
# Relationship 7261: S0070 — uses → T1071.004

**Source object:** [[01 ATT&CK/S0070 - HTTPBrowser|S0070: HTTPBrowser]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.004 - DNS|T1071.004: DNS]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HTTPBrowser](https://attack.mitre.org/software/S0070) has used DNS for command and control.(Citation: Dell TG-3390)(Citation: ThreatStream Evasion Analysis)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7eb3d9b7-8058-4d26-9196-b9a79716c5f9`.
