---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0052"
target_object: "T1090.003"
stix_relationship_id: "relationship--5b95a4a8-0cd2-457c-ba38-902ad285e5aa"
---
# Relationship 9303: C0052 — uses → T1090.003

**Source object:** [[01 ATT&CK/C0052 - SPACEHOP Activity|C0052: SPACEHOP Activity]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090.003 - Multi-hop Proxy|T1090.003: Multi-hop Proxy]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SPACEHOP Activity](https://attack.mitre.org/campaigns/C0052) has routed traffic through chains of compromised network devices to proxy C2 communications.(Citation: ORB Mandiant)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5b95a4a8-0cd2-457c-ba38-902ad285e5aa`.
