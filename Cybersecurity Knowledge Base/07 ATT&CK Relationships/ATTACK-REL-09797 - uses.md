---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0016"
target_object: "T1140"
stix_relationship_id: "relationship--e359da34-bc39-4e72-9db1-49aa5da6c8b4"
---
# Relationship 9797: C0016 — uses → T1140

**Source object:** [[01 ATT&CK/C0016 - Operation Dust Storm|C0016: Operation Dust Storm]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Operation Dust Storm](https://attack.mitre.org/campaigns/C0016), attackers used VBS code to decode payloads.(Citation: Cylance Dust Storm)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e359da34-bc39-4e72-9db1-49aa5da6c8b4`.
