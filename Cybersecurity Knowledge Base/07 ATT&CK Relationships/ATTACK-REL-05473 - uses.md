---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0145"
target_object: "T1071.004"
stix_relationship_id: "relationship--c560f682-0d21-4c9b-b35d-33aec2287117"
---
# Relationship 5473: S0145 — uses → T1071.004

**Source object:** [[01 ATT&CK/S0145 - POWERSOURCE|S0145: POWERSOURCE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.004 - DNS|T1071.004: DNS]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[POWERSOURCE](https://attack.mitre.org/software/S0145) uses DNS TXT records for C2.(Citation: FireEye FIN7 March 2017)(Citation: Cisco DNSMessenger March 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c560f682-0d21-4c9b-b35d-33aec2287117`.
