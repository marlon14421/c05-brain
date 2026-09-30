---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0066"
target_object: "T1203"
stix_relationship_id: "relationship--e1269d18-6cc9-45cc-9c99-06f765bea366"
---
# Relationship 5347: G0066 — uses → T1203

**Source object:** [[01 ATT&CK/G0066 - Elderwood|G0066: Elderwood]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1203 - Exploitation for Client Execution|T1203: Exploitation for Client Execution]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Elderwood](https://attack.mitre.org/groups/G0066) has used exploitation of endpoint software, including Microsoft Internet Explorer Adobe Flash vulnerabilities, to gain execution. They have also used zero-day exploits.(Citation: Symantec Elderwood Sept 2012)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e1269d18-6cc9-45cc-9c99-06f765bea366`.
