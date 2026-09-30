---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0085"
target_object: "T1090.003"
stix_relationship_id: "relationship--50f68fb8-1e59-4b3a-b389-9c2797f4d347"
---
# Relationship 8679: G0085 — uses → T1090.003

**Source object:** [[01 ATT&CK/G0085 - FIN4|G0085: FIN4]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090.003 - Multi-hop Proxy|T1090.003: Multi-hop Proxy]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FIN4](https://attack.mitre.org/groups/G0085) has used [Tor](https://attack.mitre.org/software/S0183) to log in to victims' email accounts.(Citation: FireEye Hacking FIN4 Dec 2014)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--50f68fb8-1e59-4b3a-b389-9c2797f4d347`.
